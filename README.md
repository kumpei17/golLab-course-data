# golLab-course-data

ゴルフ場の公式サイトにアクセスする収集ツール「golLab-course-data」の説明と連絡先のページです。

## 何をするツールか

- 個人で開発しているゴルフのスコア管理アプリのために、ゴルフ場の公式サイトに載っているコース情報を集めます。集めるのは各ホールのパー、ティー別のヤード、ハンディキャップです。
- いまは関東のゴルフ場で試している段階です。

## アクセスのしかた

- User-Agent：`golLab-course-data/0.1.0 (+https://github.com/kumpei17/golLab-course-data)`
- robots.txt に従います。
- 同じサイトへは5秒以上の間隔をあけてアクセスします。
- 取りに行くのは、コース紹介やスコアカードなどコース情報が載ったページと、そこに置かれたPDF・画像だけです。1サイトあたり数十件までです。
- 一度取得したページは手元に保存し、同じページを何度も取りに行きません。保存したページそのものを公開・再配布することはありません。
- 利用規約で自動での取得が禁止されているサイトからは取得しません。

## アクセスの停止・除外のご依頼

サイトを運営されている方で、アクセスの停止や除外をご希望の場合は、このリポジトリの [Issues](https://github.com/kumpei17/golLab-course-data/issues) でお知らせください。確認のうえ、すぐに対象から外します。

---

## English

This page describes **golLab-course-data**, a small crawler that reads golf course information (par, yardage by tee and handicap for each hole) from golf courses' official websites, for a personal golf score app in development. It is currently being tested on courses in the Kanto region of Japan.

- User-Agent: `golLab-course-data/0.1.0 (+https://github.com/kumpei17/golLab-course-data)`
- It obeys robots.txt and waits at least 5 seconds between requests to the same site.
- It fetches only pages, PDFs and images that show course information, a few dozen at most per site. Fetched pages are kept locally so they are not fetched again, and they are never republished.
- It does not crawl sites whose terms of use prohibit automated access.

If you run a site and want this crawler to stop visiting it, please open an [issue](https://github.com/kumpei17/golLab-course-data/issues) in this repository. We will exclude your site promptly.
