
# 🌀 Edge-Based Pixel Sorter

This project is a **Pixel Sorting** tool driven by **edge detection**, written in Python using OpenCV, Pillow, and Matplotlib. The idea is to transform an image into a glitch-art aesthetic by sorting its pixels vertically based on detected edges — an artistic form of image corruption often seen in generative art.

---

## 📸 Example

![Pixel Sorted Sample](sorted_image1.png)
*Above: A photo manipulated using edge-based pixel sorting.*

---

## 🔧 Features

* Load and display any image
* Apply **Canny Edge Detection** to find edge-based boundaries
* Detect **contiguous black pixel regions** (edges) in columns
* **Sort pixels** between these boundaries vertically
* Save or display the resulting glitched image

---

## 📁 Project Structure

```
pixel-sort.ipynb        # Jupyter Notebook for experimentation and execution
sorted_image1.png       # Example output
wallpapers/             # Folder containing input images
```

---

## 🛠️ Requirements

Install dependencies with pip:

```bash
pip install numpy opencv-python matplotlib pillow
```

---

## 🚀 How to Use

1. **Put your image** in a folder, e.g. `wallpapers/`
2. **Open the notebook** `pixel-sort.ipynb` in Jupyter or VS Code
3. Change the image path in the code:

```python
image_path = r'wallpapers/your-image.jpg'
```

4. Run the notebook cells to:

   * Load and display the original image
   * Convert it to grayscale
   * Apply Canny edge detection
   * Find vertical contiguous edge regions
   * Sort pixels vertically between edge bounds

5. Save the output using:

```python
output_image.save("sorted_image1.png")
```

---

## 📌 TODO

* Add support for horizontal sorting
* Allow interactive parameter tuning (thresholds, sorting direction)
* Batch process multiple images
* Export GIFs or MP4s of glitch animations

---

## 📄 License

This project is open-source and available under the **MIT License**.
You are free to use, modify, and distribute it with attribution.

