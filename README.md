![Banner](banner.png)

# cvs-PolyglotCodeSynthesizer
Generates a short intentionally vulnerable snippet for one chosen pattern (xss, sql_injection or command_injection) from fixed templates with a random string filling part of the length, and writes it to a file. The --languages argument is accepted and required, but the templates are plain text and the languages do not change the generated snippet; no language specific parsing is performed. - Focused on Tools designed to automatically generate vulnerable code snippets based on common vulnerability patterns (e.g., SQL injection, XSS, command injection). This facilitates training and testing of security scanners and code analysis tools, as well as enabling developers to understand and avoid specific vulnerabilities.

## Install
`git clone https://github.com/ShadowStrikeHQ/cvs-polyglotcodesynthesizer`

## Usage
`./cvs-polyglotcodesynthesizer [params]`

## Parameters
- `-h`: Show help message and exit
- `--vulnerability`: No description provided
- `--languages`: The target languages/interpreters for the polyglot snippet.
- `--length`: No description provided
- `--output_file`: The file to write the generated code snippet to. If not specified, a random filename is generated in the output directory.
- `--offensive`: Generate snippet suitable for direct execution (more 

## License
Copyright (c) ShadowStrikeHQ
