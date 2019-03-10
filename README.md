# Open-Source Website Audit Reports

You will find here a series of reports that can help you identify areas for improvement on your or someone else's website.

The reports contain a list of best practices recognised as important by the community who research and work in the web development industry. However, we don't pretend to know everything. We want to share with you what we have learned over the years, hoping that it will allow you to provide a better experience for users and make your site more successful.

Feel free to share with the community your thoughts, experiences and best practices you follow when improving a website by submitting commits to the reports.

## A List of Audit Reports

1. Accessibility report - coming soon
2. Analytics report - coming soon
3. Conversion Rate Optimisation (CRO) report - coming soon
4. [Page Load](https://github.com/MarcinKilarski/website-audit/blob/master/page-load/page-load-report.md) report - over 20 checks

   - [Instructions](https://github.com/MarcinKilarski/website-audit/blob/master/page-load/page-load-instructions.md)
   - [Page Load report in Microsoft Word](https://github.com/MarcinKilarski/website-audit/blob/ffcfe527fe5a734af08cb6a03d0c95a9613d5017/page-load/page-load-report.docx)
   - [Instructions in Microsoft Word](https://github.com/MarcinKilarski/website-audit/blob/ffcfe527fe5a734af08cb6a03d0c95a9613d5017/page-load/page-load-instructions.docx)

5. Security report - coming soon
6. [Search Engine Optimisation (SEO)](https://github.com/MarcinKilarski/website-audit/blob/master/seo/seo-report.md) report - over 100 checks

   - [Instructions](https://github.com/MarcinKilarski/website-audit/blob/master/seo/seo-instructions.md)
   - [Search Engine Optimisation (SEO) report in Microsoft Word](https://github.com/MarcinKilarski/website-audit/blob/2ce0f104c0ae6f9aa62f1240f2772969f60c5fe1/seo/seo-report.docx)
   - [Instructions in Microsoft Word](https://github.com/MarcinKilarski/website-audit/blob/2ce0f104c0ae6f9aa62f1240f2772969f60c5fe1/seo/seo-instructions.docx)

7. User Experience report - coming soon

## Converting Latest Markdown Files into Microsoft Word Document

Follow the instructions below to convert the most up-to-date version of the report into Word file.

1. Install [Pandoc](https://pandoc.org/) on your computer
2. Open a directory in the Terminal
3. Type:

find ./ -iname "*.md" -type f -exec sh -c 'pandoc "${0}" -o "${0%.md}.docx"' {} \;

4. Press the enter key

## An Open-Source License

License: MIT license

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
