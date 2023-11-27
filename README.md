# Automatic Picture Drawing

This project utilizes Python's `turtle` module and `svgpathtools` library to automatically draw an image specified in SVG format. The drawn image consists of filled areas represented by black spots.

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/automatic-picture-drawing.git
   ```

2. Replace the existing SVG file (test.svg) in the project directory with your own SVG image.

3. Run the draw_picture.py script:

   ```bash
   python draw_picture.py
   ```

4. The turtle graphics window will open, and the image will be drawn with black-filled areas.

## Customization

- **Scale:** You can adjust the `scale` parameter in the `sih` class to control the size of the drawn image.

- **Offsets:** Modify the `x_offset` and `y_offset` parameters to adjust the position of the drawn image.

- **Retaining the Drawing Window:** By default, the drawing window closes after completing the drawing. If you want to keep the window open, set the `retain` parameter to `True` in the `draw` method call.

## Example

```python
pen = draw_picture('path/to/your/image.svg', scale=80)
pen.draw()
```

Feel free to explore and experiment with different SVG images to create unique drawings!

## Dependencies

- `turtle`
- `cv2`
- `svgpathtools`
- `tqdm`

## Contributing

Contributions are welcome! If you have suggestions, find any issues, or want to enhance the project, feel free to submit pull requests or open issues.

##License

This project is licensed under the MIT License.

