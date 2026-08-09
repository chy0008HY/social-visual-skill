# Social Visual Skill

這是一個供 Codex 使用的社群視覺整合 skill。它協調兩個公開 skill：

- `baoyu-xhs-images`：規劃並生成社群輪播圖卡。
- `humanizer`：校正貼文、CTA 與圖卡文字，使語氣更自然。

整合入口位於 `social-visual-studio/SKILL.md`。工作流程會先確認平台、受眾與目標，完成文案及語氣校正後才生成圖卡，避免圖片完成後才修改文字。

## 安裝依賴

使用 Codex 的 skill installer，分別從下列公開來源安裝：

- `JimLiu/baoyu-skills` 的 `skills/baoyu-xhs-images`
- `blader/humanizer` repository 根目錄

接著把 `social-visual-studio` 複製到 Codex 的 skills 目錄。重新開啟一個 Codex 對話後即可使用 `$social-visual-studio`。

## 使用範例

> 使用 $social-visual-studio，把這篇文章改成 6 張 Instagram 輪播圖，語氣自然、資訊清楚，最後加入一個 CTA。

## 第三方來源

授權與來源紀錄位於 `social-visual-studio/references/sources.md`。本 repository 不包含兩個上游 skill 的完整副本；安裝時取得最新版本，並保留原作者的授權聲明。
