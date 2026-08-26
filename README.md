# Java Snippets for Zed

Handy Java code snippets for the [Zed](https://zed.dev) editor: `class`, `psvm`, `sout`, `ctor`, `for`/`fore`, `try`, `get`/`set`, and a standalone `pkg` snippet.

## Snippets

| Prefix  | Description                     |
| ------- | -------------------------------- |
| `pkg`   | `package` declaration            |
| `class` | `package` + `public class` skeleton |
| `psvm`  | `public static void main`        |
| `sout`  | `System.out.println(...)`        |
| `soutf` | `System.out.printf(...)`         |
| `ctor`  | Constructor                      |
| `fori`  | Indexed `for` loop                |
| `fore`  | Enhanced `for` (for-each) loop    |
| `try`   | `try` / `catch`                  |
| `get`   | Getter method                    |
| `set`   | Setter method                    |

## Installing

Install from the Zed extensions page by searching for "Java Snippets".

## Developing locally

1. Clone this repository.
2. In Zed, open the Command Palette and run `zed: install dev extension`.
3. Select this repository's directory.
4. Edit `snippets/java.json` and reload the extension to test changes.

## Limitations

Zed's snippet engine does not yet support snippet variables (e.g. `$TM_FILENAME_BASE`), so the class name and package name are plain tab stops you fill in manually rather than being auto-derived from the file name or folder path.
