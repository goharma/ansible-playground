🔤 String Manipulation
- upper, lower, capitalize, title: Change case
- replace: Replace substrings
- trim: Remove whitespace
- regex_replace: Apply regex substitutions
- join: Combine list elements into a string
📋 List & Dictionary Operations
- sort, unique, flatten, length: List utilities
- first, last, min, max: Element access
- dict2items, items2dict: Convert between dicts and lists
- select, reject, map, zip: Filter and transform collections
- combine: Merge dictionaries
🔢 Type Conversion & Defaults
- int, float, bool, string: Cast types
- default: Provide fallback values
- ternary: Conditional logic
- type_debug: Inspect variable type
📁 Path & File Filters
- basename, dirname, realpath, splitext: File path manipulation
- expanduser: Resolve ~ to home directory
📅 Date & Time
- to_datetime: Convert strings to datetime objects
- strftime: Format dates
- human_to_seconds: Convert human-readable time to seconds
🔐 Hashing & UUID
- hash, password_hash: Generate hashes
- uuid: Generate UUIDs
🌐 Network Filters
- ipaddr, ipv4, ipv6: IP address validation and conversion
- subnet: Extract subnet info
🧪 Debugging & Safety
- mandatory: Enforce required variables
- omit: Skip undefined or optional values
These filters can be chained together for powerful transformations, like:
{{ my_string | lower | replace('error', 'warning') | trim }}


Want examples tailored to a specific use case—like filtering WireGuard peer configs or transforming nested lists? I can help with that too.
