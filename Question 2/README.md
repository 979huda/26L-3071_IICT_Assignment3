My Mini Store:
This is a basic online store website made using standard HTML tags and tables to show different miniature items. It also has a subscription form section to let users sign up for updates and notifications.

Part 11: CSS Precedence Check
Tagline Paragraph Color:#006400(green inline)

Other p Tags Color:#8b0000(red internal)

Explanation
This happens because the browser follows a strict hierarchy rule where inline > internal > external styles. The tagline turns green because inline styles are written directly on the tag, giving them the highest specificity or "importance" weight. The other text paragraphs turn red because internal styles in the <head> are closer to the code and override the external store.css file rules.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ba7a581d-d612-4210-b025-76ad2b06332c" />
