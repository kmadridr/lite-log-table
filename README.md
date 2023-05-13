# Lite Log Table

Lite Log Table is a lightweight Python library for generating table reports and logging them to various sinks. It offers a simple and efficient solution for creating tabular reports that can be logged to different destinations, including loggers, command-line interfaces (CLI), or files.

## Features

- Generate table reports: Easily create table reports with customizable columns and rows.
- Sink options: Choose from multiple sink options to log the generated table reports, including loggers, CLI output, or file storage.
- Lightweight design: The project follows a lightweight design philosophy, focusing on simplicity, efficiency, and minimal resource usage.
- Customizable formatting: Tailor the appearance and formatting of the table reports based on your requirements.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Lite Log Table.

```bash
pip install lite-log-table
```
## Usage

1. Import the lite_log_table module into your Python project:
```python
import lite_log_table
```
2. Create a table object and define the columns and rows:
```python
table = lite_log_table.Table()
table.add_column("Name")
table.add_column("Age")
table.add_row(["John Doe", 30])
table.add_row(["Jane Smith", 25])
```
3. Choose a sink option for logging the table report. Examples:
- Logging to a logger:
```python
table.log_to_logger(logger)
```
- Logging to the command-line interface (CLI):
```python
table.log_to_cli()
```
- Logging to a file:
```python
table.log_to_file("report.txt")
```
4. Run your project and observe the table report in the desired sink.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


