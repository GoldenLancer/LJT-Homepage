# LJT-Homepage

Personal academic homepage for **Junteng Liu**, a first-year PhD candidate at the **HKUST NLP Group**, Hong Kong University of Science and Technology. Forked from [AcademicPages](https://github.com/academicpages/academicpages.github.io).

The homepage uses only personal and publication information recorded in memory. It includes academic background, research experience, research focus and interests, six publications, the Zhiyuan Honor Scholarship, and contact information. No programming languages, proficiency levels, profile photo, paper URLs, or exact publication dates have been inferred.

Only the existing About homepage and Publications subpage are published. The same six-publication list is rendered in both places. Template demonstration pages and collections are disabled, not added to the personal site.

## Content

- `_pages/about.md`: the complete personal homepage.
- `_data/publications.yml`: publication titles, authors, years, venues, authorship roles, and code-repository information from memory.
- `_includes/publication-list.html`: shared publication rendering for About and Publications.
- `_pages/publications.html`: the existing publication-list subpage.
- `_config.yml`: personal sidebar and project-site settings.
- `_data/navigation.yml`: links to homepage sections only.

The repository is hosted in the authenticated account, `GoldenLancer`. The personal GitHub contact remains `Vicent0205`, as recorded in memory. The project-site path is `/LJT-Homepage/`.

## Build

```sh
bundle install
bundle exec jekyll serve
```

The existing Jekyll workflow builds the site, checks that there are only two content pages and that all six publications appear on both, and attempts deployment to GitHub Pages.
