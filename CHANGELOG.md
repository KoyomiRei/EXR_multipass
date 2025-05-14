# Changelog

## v1.3.0 - 2025-05-14

### Duplicate Node Protection
- When pressing "Create EXR Multipass", the add-on now checks if an `EXR_multipass_output` node already exists.
- If it does, no new nodes are created. A warning appears and the viewport focuses on the existing node.

### Refresh Operator
- Added a "Refresh EXR Multipass" button in the UI.
- It updates all slots and connections without recreating the node.

### Pass Naming
- Further improvements to pass names for better clarity and consistency.

---

## v1.2.0 - 2025-05-11

### Interface
- Slight UI adjustments for better clarity.

### File Output Node
- Set label to `"EXR_multipass_output"` for easier identification.

### Pass Naming
- Some pass names have been adjusted to a more common and widely used style.

---

## v1.1.0 - 2025-05-11

- Initial release
- Created EXR multipass output setup
