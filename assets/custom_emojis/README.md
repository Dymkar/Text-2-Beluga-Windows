# Custom Emojis 🎨

This folder contains custom emoji images that can be used in your chat scripts.

## How to Add Custom Emojis

1. **Add your emoji image** (PNG, JPG, or GIF) to this folder
2. **Edit `emoji_mapping.json`** to map a name to your image file
3. **Use in your script** with the syntax `:emoji_name:`

## Example

If you have an image file `smile.png` in this folder, add it to `emoji_mapping.json`:

```json
{
    "custom_smile": "smile.png"
}
```

Then use it in your script:

```txt
Billy:
Hello everyone! :custom_smile:$^2#!message
```

## Supported Formats

- PNG (recommended for transparency)
- JPG/JPEG
- GIF (static, first frame only)

## Tips

- Use square images for best results
- Recommended size: 40x40 to 80x80 pixels
- PNG with transparency works best for custom emojis
