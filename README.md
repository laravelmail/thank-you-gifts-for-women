# Thank You Gifts For Women

Professional email template for sending thank you gifts to women in select industries, as a marketing effort.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Women Empowerment in Technology, Luxury Retail
- **Message Type:** Marketing
- **Tags:** promotion, appreciation, thank you, gift, women

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/thank-you-gifts-for-women.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/thank-you-gifts-for-women/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.thank-you-gifts-for-women',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
