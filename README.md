# Copilot Custom Models - Limited Public Beta

We’re thrilled to announce that starting today, GitHub Copilot Custom Models is now in Limited Public Beta. With Custom Models, you can fine-tune GitHub Copilot to better align with your organization’s unique coding environment. This means that your developers will receive code suggestions that are more contextually relevant, leveraging your proprietary libraries, frameworks, and even specialized languages. Imagine Copilot understanding the intricacies of your internal tools, adhering to your specific coding standards, and helping your team code faster and with greater accuracy—all while staying within your established workflows.

To get started, we’re launching this beta with selected enterprise customers who have substantial proprietary codebases, unique programming languages, or extensive internal libraries. This is your chance to shape the future of AI-enhanced development, contributing directly to how Copilot can best serve complex and specialized environments. Whether you're looking to improve the consistency of code completions or to reduce time spent on repetitive coding tasks, GitHub Copilot Custom Models offers a powerful new level of customization and productivity.

Join the beta today and experience how much more Copilot can do when it’s tailored specifically to your code. We're excited for you to test out and provide feedback as we iterate on the feature. 

## 🫂 Code of Conduct

We expect our preview participants to follow our [GitHub Community Code of Conduct](https://docs.github.com/en/site-policy/github-terms/github-community-code-of-conduct) by:

- Engaging with consideration and respect
- Contributing in a positive and constructive way
- Being trustworthy

## 🗒️ Beta Preview Policy

As per [GitHub's Terms of Service](https://docs.github.com/en/github/site-policy/github-terms-of-service#j-beta-previews) we want to remind you that:

> Beta Previews may not be supported or may change at any time. You may receive confidential information through those programs that must remain confidential while the program is private. We'd love your feedback to make our Beta Previews better.

Also, by participating in the Limited Public Beta of Copilot Custom Models, you agree to the GitHub [Pre-release Terms of Use](https://docs.github.com/en/site-policy/github-terms/github-pre-release-license-terms)

## 🔗 How to Use this Repository

We will be using this repository to centralize **early** feedback on Copilot Custom Models.

You can use this repository to file issues to:
- Up-vote a feature or request a new one.
- Search for existing issues already reported for potential workarounds.
- File a bug report.

## **[Discussions](https://github.com/gh-community/copilot-custom-models-beta/discussions)** 

Discussions should be used as much as possible for questions, ideas, and open discussions with other folks in the preview.

_Discussion Categories:_ 
- #### 💡 [I have a suggestion](https://github.com/gh-community/copilot-custom-models-beta/discussions/categories/ideas)
- #### ❓ [I have a question](https://github.com/gh-community/copilot-custom-models-beta/discussions/categories/q-a)
- #### ✏️ [I have something else to discuss](https://github.com/gh-community/copilot-custom-models-beta/discussions/categories/general)

## **[Issues](https://github.com/gh-community/copilot-custom-models-beta/issues)**

Issues should be used for bug reports.

_Issue Category:_ 
- #### 🐞 [I found a bug](https://github.com/gh-community/copilot-custom-models-beta/issues/new?assignees=&labels=bug&template=bug-template.yml)

## 🗒️ Getting Started

<!-- Include summary / details of feature here. This section should include steps to access the feature, and may include additional instructional materials such as a demo video or link out to feature documentation. -->

<!--  Examples below 
#### ℹ️ [About FEATURE NAME tokens](add-link-here.md) 
#### ⚙️ [Creating FEATURE NAME](add-link-here.md) 
#### 📦 [Using FEATURE NAME](add-link-here.md)
####  🎥 An Intro to FEATURE NAME -->

## ❓ FAQ 

## Frequently Asked Questions

### 1. What are GitHub Copilot Custom Models?

GitHub Copilot Custom Models are fine-tuned versions of the Copilot model, specifically tailored to your organization’s unique coding environment. These custom models are created using Multi-LoRA (Low-Rank Adaptation) techniques, which allow us to efficiently fine-tune the base model with your organization’s proprietary code, internal libraries, and specialized languages. The result is a Copilot that understands and adapts to the nuances of your specific codebase, providing more accurate and context-aware code suggestions that align closely with your development practices.

### 2. How do I participate in the Limited Public Beta?

To join the beta, your organization must be on a GitHub Copilot Enterprise plan. You can sign up through the provided [beta enrollment link](#). Once approved, your organization will be able to create and train custom models based on your specific coding environment.

### 3. What are the prerequisites for using Custom Models?

Your organization’s code must be hosted in GitHub repositories, and you should have a substantial proprietary codebase or use specialized programming languages. Participation in the beta also requires your developers to use GitHub Copilot in supported IDEs, where the custom models will enhance code completion scenarios.

### 4. What data is used to train Custom Models?

Custom Models are trained using your organization’s GitHub repositories and, optionally, telemetry from developer interactions with Copilot. All data used for training remains private and secure, and it is used exclusively for your custom model.

### 5. What legal terms must participants agree to for this beta?

All participants in the beta must agree to GitHub’s pre-release legal terms, which include provisions for data usage and privacy. Your organization’s admin will need to approve these terms before participating.

### 6. How will I know if my custom model is performing better?

During the beta, GitHub will work closely with your team to monitor the performance of your custom model. While there isn’t a self-serve insights portal during the beta, we will provide qualitative feedback mechanisms and support to help you assess the effectiveness of the custom model. Additionally, you can leverage the Copilot Usage Metrics API to track and timestamp the acceptance rates of code suggestions before and after your custom model is deployed. This will help you quantitatively measure improvements in how often your team accepts suggestions from Copilot, offering a clear indicator of your custom model’s impact.
