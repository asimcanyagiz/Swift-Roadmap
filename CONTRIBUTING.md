# Contributing to Swift Roadmap

[English](#english) · [Türkçe](#türkçe)

## English

Thank you for helping people learn Swift. You can contribute a clearer explanation, a small runnable example, a corrected link, or feedback from learning or teaching with the roadmap.

### Pick a small change

1. Read the [roadmap](README.md) and check existing issues and pull requests for duplicates.
2. Choose an unassigned [good first issue](https://github.com/asimcanyagiz/Swift-Roadmap/labels/good%20first%20issue). Read its scope and acceptance criteria, then leave a comment if you would like to work on it. Check for an existing contributor before starting.
3. Small typos and broken links can go straight to a pull request. Open an issue first for a new topic, a translation, or a larger restructure.

You do not need to be a Swift expert. Issue and PR discussions may be in English or Turkish. Existing topic pages use Turkish; keep new explanations in Turkish and use the established Swift API names. Keep the English and Turkish indexes in sync when adding or moving a topic.

### Make your first pull request

For a Markdown-only edit, open the file on GitHub, choose the pencil icon, and follow GitHub's fork and pull request flow. Preview the Markdown before submitting. No Xcode installation is needed for text or link edits.

If you prefer local editing:

1. Fork this repository to your own account and clone **your fork**.
2. Create a branch, for example `git switch -c docs/dictionary-example`.
3. Edit only the files needed for your chosen issue.
4. Run the checks below, commit your change, and push the branch to your fork.
5. Open a pull request against `asimcanyagiz/Swift-Roadmap`, base branch `main`. Explain the learner's problem, your change, and how you checked it. Use `Closes #123` only if your PR completes issue 123.

### Content and checks

- Write original explanations for someone learning the topic for the first time. Link to sources rather than copying their text.
- Keep examples small and self-contained. Use a fenced `swift` code block and show the expected result. Do not add personal data, credentials, or private project code.
- For a runnable snippet, paste it into a temporary `example.swift`, run `swift --version` and `swift example.swift`, and include the toolchain version and actual output in the PR. A Playground is also fine; state its Xcode version. Check the boundary case requested by the issue.
- Use Swift 5-compatible syntax for beginner language examples unless the topic needs a newer feature. State any minimum Swift or OS version. UI and framework examples may need an Xcode project; describe that setup instead of claiming a standalone script was tested.
- If you cannot run a changed example, say so in the PR so a reviewer can verify it before merge. Do not mark it as tested.
- Preview Markdown, click changed links, and check that internal links reach the intended file or heading. For an external resource, verify its title and relevance, not only its HTTP status.
- Run `git diff --check` when editing locally. Use descriptive headings and language labels on code fences. Update a page's contents list if you add a section.
- Preserve useful existing resources; explain why a link is removed or replaced. Keep one topic per PR and avoid unrelated formatting changes.

### Review and credit

A maintainer checks the scope, technical accuracy, sources, and reported validation. Respond to review comments by updating the same branch. A draft PR is welcome when you need help. Merged contributions retain their author attribution in Git history and the linked pull request.

Be respectful, welcome beginner questions, and discuss the content rather than the person. Harassment, spam, and sharing private information are not acceptable. Contributions are made under the repository's [MIT license](LICENSE); third-party resources retain their own terms.

## Türkçe

Swift öğrenenlere yardımcı olduğunuz için teşekkürler. Açıklama, küçük bir çalıştırılabilir örnek, bağlantı düzeltmesi veya öğrenme ve öğretme deneyiminizle katkı yapabilirsiniz.

### Küçük bir iş seçin

1. [Yol haritasını](README.tr.md) okuyun; benzer issue ve PR var mı kontrol edin.
2. Atanmamış bir [good first issue](https://github.com/asimcanyagiz/Swift-Roadmap/labels/good%20first%20issue) seçin. Kapsamını ve kabul ölçütlerini okuyun, çalışmak istiyorsanız yorum bırakın. Başka bir katkıcının başlamış olup olmadığını kontrol edin.
3. Küçük yazım ve bağlantı düzeltmeleri için doğrudan PR açabilirsiniz. Yeni konu, çeviri veya büyük düzenleme için önce issue açın.

Uzman olmanız gerekmez. Issue ve PR yazışmaları Türkçe veya İngilizce olabilir. Mevcut konu sayfalarına Türkçe açıklama ekleyin ve Swift API adlarını koruyun. Konu ekler veya taşırken iki dildeki dizini de güncelleyin.

### İlk pull request

Yalnızca Markdown düzenlemek için GitHub'da dosyayı açıp kalem simgesini seçin; GitHub'ın fork ve PR adımlarını izleyin. Göndermeden önce Markdown önizlemesini kontrol edin. Metin veya bağlantı düzeltmesi için Xcode gerekmez.

Yerelde çalışmak isterseniz:

1. Repoyu kendi hesabınıza fork edin ve **kendi fork'unuzu** klonlayın.
2. Bir dal oluşturun: örneğin `git switch -c docs/dictionary-example`.
3. Yalnızca seçtiğiniz işin gerektirdiği dosyaları değiştirin.
4. Aşağıdaki kontrolleri yapın; commit edip dalı kendi fork'unuza push edin.
5. Hedef repo `asimcanyagiz/Swift-Roadmap`, hedef dal `main` olacak şekilde PR açın. Öğrenenin sorununu, değişikliği ve nasıl doğruladığınızı açıklayın. `Closes #123` ifadesini yalnızca PR, 123 numaralı işi tamamlıyorsa kullanın.

### İçerik ve doğrulama

- Yeni öğrenen birinin anlayacağı özgün açıklamalar yazın. Kaynak metnini kopyalamak yerine bağlantı verin.
- Örnekleri küçük ve kendi başına çalışabilir tutun; `swift` etiketli kod bloğu ve beklenen çıktı ekleyin. Kişisel veri, erişim anahtarı veya gizli proje kodu paylaşmayın.
- Çalıştırılabilir örneği geçici bir `example.swift` dosyasına koyup `swift --version` ve `swift example.swift` çalıştırın. PR'a sürümü ve gerçek çıktıyı yazın. Playground da kullanılabilir; Xcode sürümünü belirtin. Issue'daki sınır durumunu da deneyin.
- Başlangıç örneklerinde, konu daha yeni bir özellik gerektirmiyorsa Swift 5 uyumlu sözdizimi kullanın. Gerekli minimum Swift veya işletim sistemi sürümünü belirtin. UI ve framework örnekleri Xcode projesi gerektiriyorsa kurulumunu açıklayın.
- Örneği çalıştıramadıysanız PR'da söyleyin; merge öncesi reviewer doğrulayabilsin. Çalıştırmadığınız kontrolü yapılmış olarak işaretlemeyin.
- Markdown önizlemesini ve değişen bağlantıları kontrol edin. İç bağlantının doğru dosya veya başlığa gittiğini; dış kaynağın başlığını ve konuyla ilgisini doğrulayın.
- Yerelde `git diff --check` çalıştırın. Açık başlıklar ve kod bloklarında dil etiketi kullanın. Bölüm eklerseniz sayfanın içindekiler listesini güncelleyin.
- Yararlı mevcut kaynakları koruyun; bir bağlantıyı kaldırıyor veya değiştiriyorsanız nedenini yazın. Her PR'ı bir konuyla sınırlayın.

### İnceleme ve katkı kaydı

Maintainer kapsamı, teknik doğruluğu, kaynakları ve doğrulamayı kontrol eder. Yorumlara aynı dalı güncelleyerek yanıt verin. Yardım istiyorsanız taslak PR açabilirsiniz. Merge edilen katkının yazarı Git geçmişinde ve PR'da görünür.

Saygılı olun, başlangıç sorularına alan açın ve kişiyi değil içeriği tartışın. Taciz, spam ve özel bilgi paylaşımı kabul edilmez. Katkılar reponun [MIT lisansı](LICENSE) kapsamında sunulur; üçüncü taraf kaynaklar kendi koşullarını korur.
