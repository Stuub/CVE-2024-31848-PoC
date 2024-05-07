# Exploiting CData within Jetty servers - CVE-2024-31848/49/50/51 - File Path Traversal & File Read

## What it is

A prototype PoC for the automation of vulnerability analysis on targets running CData applications on an embedded Jetty server.

## Usage 

Just use `-u` or `--url` to specify your target, the script will attempt to retrieve the `getSettings.rsb?` file, present within all CData instances.

## Example

![image](https://github.com/Stuub/CVE-2024-31848-PoC/assets/60468836/778ad753-0abb-45e6-b157-bde723839067)


## Notes

More error handling to be added in future

## Disclaimer

Please use responsibly, exploitability is extremely high with this vulnerability. Only test within your own authorised limitations.
