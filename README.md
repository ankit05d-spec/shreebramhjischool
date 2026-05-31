# Shree Brahma Ji Adarsh HP School Website

## 🏫 School Information

**School Name:** Shree Brahma Ji Adarsh HP School

**Address:** Muhammada Barwapatti Motichak, Kushinagar, Uttar Pradesh

**Classes:** Nursery to Class 6

**Government Recognition:** Uttar Pradesh Government (Since 2008-09)

**UDISE Code:** 09590703204

---

## 👨‍💼 Leadership

### Founder
**Shree Gautam Muni Tiwari**
- Senior Urban Journalist
- Visionary Educationist
- Phone: +91-94502-31827

### Principal
**Shree Vijendra Kumar Tiwari**
- Phone: +91-99841-35693

---

## 📄 Website Pages

### 1. **Home** 🏠
- School introduction
- Key features
- Photo gallery placeholder
- Quick overview

### 2. **About Us** ℹ️
- School history
- Mission & Vision
- Core principles
- Leadership information
- Staff details

### 3. **Academics** 📚
- Classes offered (Nursery to 6)
- Curriculum information
- Subject details
- Time table
- Co-curricular activities

### 4. **Admission** 📝
- Online admission form
- Student information fields
- Parents information
- Photo upload capability
- Fee structure
- Admission process
- ID card generation system

### 5. **News & Events** 📰
- Latest news
- Upcoming events
- Cultural activities
- Photo gallery
- School achievements

### 6. **Contact** 📞
- School address
- Contact numbers
- Leadership contact info
- Contact form
- Important school details

---

## 🖼️ How to Upload Photos

### Method 1: Upload via GitHub Web Interface

1. Go to your repository: https://github.com/ankit05d-spec/shreebramhjischool

2. Click **Add file** → **Upload files**

3. Create a **photos** folder by:
   - Drag and drop images
   - Name them like: `photos/event-1.jpg`, `photos/campus-1.jpg`

4. After uploading, get the **raw GitHub URL**:
   - Click on the image file
   - Click **Raw** button
   - Copy the URL

5. The URL will look like:
   ```
   https://raw.githubusercontent.com/ankit05d-spec/shreebramhjischool/school-website/photos/image-name.jpg
   ```

### Method 2: Add Images to Gallery

Edit `index.html` and update the photo gallery section:

```html
<div class="gallery" id="photoGallery">
    <div class="gallery-item">
        <img src="https://raw.githubusercontent.com/ankit05d-spec/shreebramhjischool/school-website/photos/event-1.jpg" alt="Event 1">
    </div>
    <div class="gallery-item">
        <img src="https://raw.githubusercontent.com/ankit05d-spec/shreebramhjischool/school-website/photos/campus-1.jpg" alt="Campus">
    </div>
</div>
```

### Step-by-Step Photo Upload Instructions

#### Step 1: Prepare Your Images
- Use JPG or PNG format
- Resize to 600x400 pixels (recommended)
- Name clearly (e.g., `sports-day-2024.jpg`)

#### Step 2: Upload to Repository
```bash
1. Go to: https://github.com/ankit05d-spec/shreebramhjischool
2. Click "Add file" (top right)
3. Select "Upload files"
4. Drag and drop your images
5. Type commit message: "Add school photos"
6. Click "Commit changes"
```

#### Step 3: Get Image URL
```bash
1. Click on uploaded image
2. Click "Raw" button (top right)
3. Copy the full URL from address bar
4. This is your image link!
```

#### Step 4: Add to Website
```html
<!-- Find this in index.html -->
<div class="gallery" id="photoGallery">
    <!-- Add your image here -->
    <div class="gallery-item">
        <img src="PASTE_YOUR_URL_HERE" alt="School Event">
    </div>
</div>
```

---

## 📱 Features

✅ **Responsive Design** - Works on mobile, tablet, and desktop

✅ **Modern UI** - Clean, professional appearance

✅ **Online Forms** - Admission and contact forms

✅ **Photo Gallery** - Showcase school events and activities

✅ **Complete Information** - All school details in one place

✅ **Easy Navigation** - Simple menu system

✅ **Government Details** - UDISE code and recognition info

---

## 🔧 How to Customize

### Edit School Information
1. Open `index.html` in a text editor
2. Find the text you want to change
3. Edit and save
4. Upload the file back to GitHub

### Update Contact Numbers
Find and replace:
- `+91-94502-31827` (Founder's number)
- `+91-99841-35693` (Principal's number)

### Add Fee Structure
Find the Fee Structure table and update amounts:
```html
<td>₹ [Add Amount]</td>
```

### Update Photo Gallery
Add image URLs to the gallery section (see instructions above)

---

## 📚 Admission Form Fields

- Student Name (First & Last)
- Date of Birth
- Height & Weight
- Blood Group
- Aadhar Number
- Complete Address
- Father's Name & Phone
- Mother's Name
- Alternate Contact
- Student Photo
- Class Applying For

---

## 💾 File Structure

```
shreebramhjischool/
├── index.html          # Main website file
├── README.md          # This file
└── photos/            # School photos folder
    ├── event-1.jpg
    ├── campus-1.jpg
    └── ... more images
```

---

## 🌐 Accessing Your Website

Once live, access at:
https://github.com/ankit05d-spec/shreebramhjischool

Or view the HTML file directly in a browser.

---

## 📝 Notes

- Forms are front-end only (messages don't send automatically)
- To make forms functional, you'll need a backend service or form handler
- Photos must be uploaded manually through GitHub interface
- Website is fully responsive and mobile-friendly

---

**Last Updated:** 2024

**Website Version:** 1.0
