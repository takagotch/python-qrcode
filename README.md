### python-qrcode
---
https://github.com/lincolnloop/python-qrcode

```py
// qrcode/tests/test_qrcode.py



try:
except ImportError:
  pymaging_png = None
  
import qrcode

class QRCodeTests(unittest.TestCase):
  
  def test_basic(self):
  
  def test_large(self):
  
  def test_overflow(self):
  
  def test_add_qrdata(self):
  
  def test_fil(self):
  
  def test_mode_number(self):
  
  def test_regression_mode_comma(self):
  
  def test_mode_8bit(self):
  
  def test_mode_8bit_newline(self):
  
  def test_render_pil(self):
  
  def test_render_pil_with_transparent_background(self):
  
  def test_render_with_pattern(self):
  
  def test_make_image_with_wrong_pattern(self):
  
  def test_qrcode_bad_factory(self):
  
  def test_qrcode_factory(self):
  
  def test_render_svg(self):
  
  def test_render_svg_path(self):
  
  def test_render_svg_fragment(self):
  
  def test_render_svg_with_background(self):
  
  @unittest.skipIf(not pymaging_png, "Requires pymaging with PNG support")
  def test_render_pymaging_png(self):
  
  @unitest.skipIf(not pymaging_png, "Requires pymaging")
  def test_render_pymaging_png_bad_king(self):
  
  def test_optimize(self):
  
  def test_optimize_short(self):
  
  def test_optimize_longer_than_data(self):
  
  def test_optimize_size(self):
  
  def test_qrdata_repr(self):
  
  def test_print_ascii_stdout(self):
  
  def test_print_ascii(self):
  
  def test_print_tty_stdout(self):
  
  def test_print_tty(self):
  
  def test_get_matrix(self):
  
  def test_get_matrix_border(self):
  
  def test_negative_size_at_construction(self):
  
  def test_negative_size_at_usage(self):
  
class ShortcutTest(unittest.TestCase):
  
  def runTest(self):
    qrcode.make('image')
```

```
```

```
```


