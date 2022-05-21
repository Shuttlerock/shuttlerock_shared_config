[JIRA Story Link]( www.add-link-here )

Copy and paste JIRA description here

## Type of change
Select all that apply:
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Security issue
- [ ] Infrastructure / network
- [ ] Refactoring
- [ ] Functional improvement

## What changed?

#### Before

（エラーの）条件があれば、ここに書いてください。
You clicked a button and it gave error

#### After

開発後の結果
When you click the button, it does the thing.


## How to test the PR

#### Preparation: 
テスト用の条件、準備を書いてください。
Prepare something before tests

#### Tests
Some page > Subpage (どこでテストをします)

- Select something　（やること）
- Click button　（やること）
  - Success when something happens　（結果）

Add screenshot if applicable　（スクショ）

- Select something else　（やること）
- Click button　（やること）
  - Success when something else happens　（結果）

Add screenshot if applicable　（スクショ）

---

**Regression:** If there were any substantial changes to view layer code (CSS, JS) or Javascript dependencies were updated do a general smoke test of the feature using the following Windows 7 browsers on Browser Stack. If Chrome only is chosen, only Chrome is tested normally without any other browsers.

Chromeだけが選択だったら、他のブラウザーのテストは不要です。

- [x] Chrome (Latest)
- [ ] Firefox (Latest)
- [ ] Internet Explorer 11

## Deployment Notes

It requires new Environmental variables:

- `EXAMPLE_ENV_VARIABLE=content`
- `EXAMPLE_ENV_VARIABLE2=content`
