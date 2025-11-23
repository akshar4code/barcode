# Godex G500 Printer Setup Guide

## Problem: Blank Pages Printing

If your Godex G500 is printing blank pages, follow these steps:

---

## 1. Browser Print Settings (Chrome/Edge)

When you click "Print Label (60x45mm)":

1. **Select Printer**: Choose "Godex G500" from the printer list
2. **Paper Size**: 
   - Click "More settings"
   - Paper size: Select "Custom" or "User Defined"
   - Enter: **60mm x 45mm** (or 2.36" x 1.77")
3. **Scale**: Set to **100%** or "Actual size"
   - ❌ DO NOT select "Fit to page"
   - ❌ DO NOT select "Shrink to fit"
4. **Margins**: 
   - Set to **None** or **0mm** for all sides
5. **Orientation**: 
   - Try **Landscape** first (60mm width, 45mm height)
   - If that doesn't work, try **Portrait**

---

## 2. Godex G500 Driver Settings

### Windows:
1. Go to **Control Panel** → **Devices and Printers**
2. Right-click **Godex G500** → **Printing Preferences**
3. Set:
   - **Paper Size**: Custom → 60mm x 45mm
   - **Print Speed**: Medium (adjust if needed)
   - **Darkness**: 10-15 (adjust based on label quality)
   - **Print Mode**: Thermal Transfer or Direct Thermal (based on your labels)

### Mac:
1. Go to **System Preferences** → **Printers & Scanners**
2. Select **Godex G500**
3. Click **Options & Supplies** → **Driver**
4. Set paper size to **60mm x 45mm**

---

## 3. Label Stock Configuration

Make sure your physical labels match:
- **Width**: 60mm
- **Height**: 45mm
- **Gap**: Check if your labels have gaps between them
- **Label Type**: Continuous or gap labels

In Godex driver:
- Set **Media Type** to match your labels (Gap/Black Mark/Continuous)
- Run **Auto Calibration** to detect label size

---

## 4. Test Print Steps

1. **Generate a label** in the web application
2. Click **"Print Label (60x45mm)"**
3. In print dialog:
   - Verify printer: Godex G500
   - Verify paper size: 60mm x 45mm
   - Verify scale: 100%
4. Click **Print**

---

## 5. Common Issues & Solutions

### Issue: Still printing blank
**Solution**: 
- Check if label roll is loaded correctly
- Run printer self-test (hold FEED button while turning on)
- Calibrate the printer (see manual)

### Issue: Only partial content prints
**Solution**:
- Reduce number of fields (use fewer custom fields)
- Check if paper size is correctly set to 60mm x 45mm
- Ensure scale is 100%, not "fit to page"

### Issue: Content is too small
**Solution**:
- The app automatically adjusts font size based on field count
- With fewer fields (1-5), fonts will be larger
- With more fields (10+), fonts will be smaller

### Issue: Barcode not scanning
**Solution**:
- Increase printer darkness setting
- Ensure barcode is not cut off
- Check barcode number is valid (no special characters)

---

## 6. Alternative: Print to PDF First

If direct printing doesn't work:

1. Click **"Print Label (60x45mm)"**
2. Select **"Save as PDF"** instead of printer
3. Open the PDF
4. Print PDF to Godex G500 with settings:
   - Paper: 60mm x 45mm
   - Scale: 100%
   - Margins: 0

---

## 7. Browser Compatibility

**Best browsers for printing**:
- ✅ Google Chrome (Recommended)
- ✅ Microsoft Edge
- ⚠️ Firefox (may have scaling issues)
- ⚠️ Safari (may need adjustments)

---

## 8. Quick Checklist

Before printing, verify:
- [ ] Godex G500 is selected as printer
- [ ] Paper size: 60mm x 45mm
- [ ] Scale: 100% (Actual size)
- [ ] Margins: 0 or None
- [ ] Labels are loaded in printer
- [ ] Printer is calibrated
- [ ] Test print works from printer itself

---

## Need Help?

If you're still experiencing issues:
1. Run printer self-test to verify hardware works
2. Check printer manual for calibration steps
3. Verify label dimensions match physical labels
4. Try printing from a different browser
5. Update Godex printer driver to latest version

---

## Technical Details

The web application is configured for:
- **Page Size**: Exactly 60mm x 45mm
- **Dynamic Font Sizing**: Adjusts based on field count
- **Print Optimization**: Thermal printer compatible
- **Layout**: Product details → Custom fields → Barcode
