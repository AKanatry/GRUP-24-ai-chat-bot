# 🤖 Yapay Zeka Destekli Sohbet Sistemi (AI Chat Bot)

![Project Status](https://img.shields.io/badge/Status-Tamamland%C4%B1-success)
![Next.js](https://img.shields.io/badge/Next.js-14-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![Prisma](https://img.shields.io/badge/Prisma-ORM-green)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-3.8-blue)

Bu proje, modern web teknolojileri ve büyük dil modelleri (LLM) kullanılarak geliştirilmiş, gerçek zamanlı bir sohbet uygulamasıdır. Kullanıcıların yapay zeka (Gemini, GPT vb.) ile akıcı bir şekilde sohbet etmesini, geçmiş konuşmalarını kaydetmesini ve yönetmesini sağlar. Yazılım Mühendisliği dersi projesi kapsamında geliştirilmiştir.

## 📸 Ekran Görüntüleri (Screenshots)

Uygulamanın arayüzü, kullanıcı deneyimini ön planda tutarak hem aydınlık hem de karanlık mod seçenekleriyle tasarlanmıştır.

| **Aydınlık Mod (Light Mode)** | **Karanlık Mod ve Geçmiş (Dark Mode)** |
|:-------------------------:|:----------------------------------:|
| ![Light Mode](./public/screenshots/light-mode.png) | ![Dark Mode](./public/screenshots/dark-mode.png) |
| *Sade ve anlaşılır sohbet arayüzü* | *Yan menü ile geçmiş sohbetlere erişim* |

| **Örnek Sohbet Senaryosu** |
|:-------------------------:|
| ![Chat Demo](./public/screenshots/chat-demo.png) |
| *Ders kapsamına özel uyarlanmış yanıtlar ve model seçimi* |

## 🚀 Özellikler

* **Gerçek Zamanlı Yanıt (Streaming UI):** Yapay zeka yanıtları, kelime kelime ekrana yansıtılır (Vercel AI SDK).
* **Çoklu Model Desteği:** Gemini ve diğer modeller arasında seçim yapabilme imkanı.
* **Sohbet Geçmişi:** Tüm konuşmalar veritabanında saklanır, sol menüden yönetilebilir.
* **Güvenli Oturum Açma:** NextAuth.js ile güvenli kimlik doğrulama.
* **Tema Desteği:** Göz yormayan Karanlık Mod ve Aydınlık Mod seçenekleri.
* **Markdown Desteği:** Kod blokları, listeler ve kalın metinler düzgün formatta görüntülenir.

## 🛠️ Kullanılan Teknolojiler (Tech Stack)

* **Framework:** [Next.js 14](https://nextjs.org/) (App Router)
* **Dil:** [TypeScript](https://www.typescriptlang.org/)
* **Yapay Zeka:** [Vercel AI SDK](https://sdk.vercel.ai/docs) & Google Gemini API
* **Veritabanı:** [PostgreSQL](https://www.postgresql.org/)
* **ORM:** [Prisma](https://www.prisma.io/)
* **Stil:** [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/)

## ⚙️ Kurulum ve Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

### 1. Projeyi Klonlayın
```bash
git clone [https://github.com/KULLANICI_ADI/AI_ChatBot.git](https://github.com/KULLANICI_ADI/AI_ChatBot.git)
cd AI_ChatBot
