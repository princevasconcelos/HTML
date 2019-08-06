# HTML

## Images

```js
<picture>
    <source
        srcset="/some/_1170x658_crop_center-center/man-with-a-dog.webp 1170w,
                /some/_970x545_crop_center-center/man-with-a-dog.webp 970w,
                /some/_750x562_crop_center-center/man-with-a-dog.webp 750w,
                /some/_320x240_crop_center-center/man-with-a-dog.webp 320w"
        sizes="100vw"
        type="image/webp"
    />
    <source
        srcset="/some/_1170x658_crop_center-center/man-with-a-dog.jpg 1170w,
                /some/_970x545_crop_center-center/man-with-a-dog.jpg 970w,
                /some/_750x562_crop_center-center/man-with-a-dog.jpg 750w,
                /some/_320x240_crop_center-center/man-with-a-dog.jpg 320w"
        sizes="100vw"
    />
    <img
        src="/some/man-with-a-dog-placeholder.jpg"
        alt="Man with a dog"
        style="object-fit: cover;"
        loading="lazy"
    />
</picture>
```
