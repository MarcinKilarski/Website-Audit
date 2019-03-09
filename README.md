# Open-Source Website Audit Reports

You will find here a series of reports that can help you identify areas for improvement on your or someone else's website.

The reports contain a list of best practices recognised as important by the community who research and work in the web development industry. However, we don't pretend to know everything. We want to share with you what we have learned over the years, hoping that it will allow you to provide a better experience for users and make your site more successful.

Feel free to share with the community your thoughts, experiences and best practices you follow when improving a website by submitting commits to the reports.

## A List of Audit Reports

1. Accessibility - coming soon
2. Analytics - coming soon
3. Conversion Rate Optimisation (CRO) - coming soon
4. Security - coming soon
5. [Search Engine Optimisation (SEO)](https://github.com/MarcinKilarski/website-audit/blob/master/seo/seo-report.md) - over 100 checks

   - [Instructions](https://github.com/MarcinKilarski/website-audit/blob/master/seo/seo-instructions.md)

6. User Experience - coming soon
7. [Web Performance (Page Load)](https://github.com/MarcinKilarski/website-audit/blob/master/web-performance/web-performance-report.md) - over 20 checks

   - [Instructions](https://github.com/MarcinKilarski/website-audit/blob/master/web-performance/web-performance-instructions.md)

## Converting Markdown Files into Word

Follow the instructions below to convert the most up-to-date version of the report into Word file.

1. Install [Pandoc](https://pandoc.org/) on your computer
2. Open a directory in Terminal
3. Type in:

find ./ -iname "*.md" -type f -exec sh -c 'pandoc "${0}" -o "${0%.md}.docx"' {} \;

4. Press enter key

## An Open-Source License

License: MIT license

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
