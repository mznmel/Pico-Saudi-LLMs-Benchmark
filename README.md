```
Disclaimer: All the answers are generated by A.I. models with no human intervention. The liability of the answers is solely on the models and not on the project creator.
```

# Pico-Saudi-LLMs-Benchmark

أهلاً وسهلاً، من الأسئلة المتكررة مؤخراً: ماهو أفضل نموذج لغوي يتعامل مع اللغة العربية؟ وسؤال آخر، أي نموذج لغوي يعمل يفهم الثقافة السعودية بشكل جيد؟
عادة للإجابة على هذا السؤال، نحتاج إجراء إختبارات يدوية ومقارنة النتائج بشكل يدوي، ولتسهيل العملية جمعت مجموعة من الأسئلة باللغة العربية وجزء كبير منها يتعلق بشكل مباشر بالثقافة السعودية وجربتها على عدد من النماذج اللغوية.

بإمكانك الإطلاع على الأسئلة و النتائج داخل المجلدات الموجودة في هذا المشروع، داخل المجلد حتجد قائمة الأسئلة بصيغة CSV و نتائج النماذج المختلفة في ملفات Markdown لتسهيل القراءة، كل ملف مسمى بإسم النموذج اللغوي الذي أنتج الإجابات.

التركيز في النسخة الأولى من مجموعة البيانات على الأسئلة البسيطة المباشرة فقط لإختبار قدرات النماذج على فهم الأسئلة والإجابة عليها بطريقة صحيحة.

الـ System Prompt لكل النماذج أثناء الإختبار هو:
```
You must provide all your responses exclusively in Arabic
```
لبعض النماذج أضفنا جملة
```
Plain Text Only
```
لتفادي الإجابات بصيغة Markdown أو HTML.

الهدف ليس عمل إختبار متكامل لهذه النماذج اللغوية بل فقط  رؤية نتائجها للتمكن من مقارنتها بشكل بدائي سريع.

| Company           | Model Name                  | Parameters | Results Link                                           |
|-------------------|-----------------------------|------------|--------------------------------------------------------|
| Meta              | LLama 3.1                   | 70B        | [Meta LLama 3.1 70B Instruct](v0.01/results/meta-llama-3-70b-instruct.md) |
| Meta              | LLama 3.1                   | 405B       | [Meta LLama 3.1 405B Instruct](v0.01/results/meta-llama-3.1-405b-instruct.md) |
| Google-DeepMind   | Gemma-2                     | 2B         | [Google-DeepMind Gemma-2 2b Instruct](v0.01/results/gemma-2-2b-it.md) |
| Google-DeepMind   | Gemma-2                     | 9B         | [Google-DeepMind Gemma-2 9b Instruct](v0.01/results/gemma2-9b-it.md) |
| Google-DeepMind   | Gemma-2                     | 27B        | [Google-DeepMind Gemma-2 27b Instruct](v0.01/results/gemma2-27b-it.md) |
| Microsoft         | Phi-3 Mini                  | 3.8B       | [Microsoft Phi-3 Mini 3.8b Instruct](v0.01/results/phi-3-mini-4k-instruct.md) |
| CohereForAI       | Aya-Expanse                 | 8B         | [CohereForAI Aya-Expanse 8b](v0.01/results/CohereForAI-aya-expanse-8b.md) |
| HuggingFace       | SmolLM2                     | 135M       | [HuggingFaceTB SmolLM2 135M Instruct](v0.01/results/HuggingFaceTB-SmolLM2-135M-Instruct.md) |

### [رابط الأسئلة](v0.01/Pico-Saudi-LLMs-Questions-v0.01.csv)