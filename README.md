# awesome-cka
Curated list of study materials and pratice labs to prepare for the Certified Kubernetes Administrator (CKA) Exam

>[!NOTE]
> As the name suggest this repo's aims is to curate resources for learning CKA, not just Kubernetes in general.
> While CKA is certainly about Kubernetes, it's far from covering everything there's to know about it.
> In fact, there are other CNCF Certifications that dive into other areas of Kubernetes, such as Security (CKS) and Application Development for k8s (CKAD).
> But certainly, if you study for the CKA throughly, you will have a solid grasp on Kubernetes that will empower you to solve many problems faced day to day by cluster adminstrators in real world environments.

>[!NOTE]
> I know it's tempting to save money and only use free resources.
> To be honest, it's totally possible to pass the exam by doing so. In fact, many people certainly have done that.
> But I highly recommended supporting those awesome creators by buying ther paid material, especially if you like their free content.

## Courses

### Free
1. [Kubernetes FULL COURSE 2025- Zero to Hero!](https://www.youtube.com/playlist?list=PLleCw-vqe90AqkxnzWVU8IexL7pWijxml)

### Paid
1. [Certified Kubernetes Administrator (CKA) with Practice Tests](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests)

## Videos
1. [Easy CKA Exam Tasks For Beginners! | Full Solutions & Walkthrough
](https://www.youtube.com/watch?v=rP-W3Tv3plw)
2. [2025 CKA Exam Questions & Solutions UPDATE! | Full Walkthrough!](https://www.youtube.com/watch?v=eGv6iPWQKyo)

## Labs
### Free
1. [Killercoda](https://killercoda.com/cka)
2. [CK-X](https://sailor.sh/)

### Paid
1. [Certified Kubernetes Administrator – Full Mock Exam Series - by Kodekloud](https://learn.kodekloud.com/user/courses/ultimate-certified-kubernetes-administrator-cka-mock-exam-series)
2. [Killer Shell](https://killer.sh/)

## Documentation
1. [Kubernetes Official Documentation](https://kubernetes.io/docs/home/)

## Tips & Tricks
### Master Imperative Commands
Learn how to create k8s resources using imperative commands.
Most of the common resources can be created by using kubectl imperative style
Although not recommended in production environments, it'll certainly save you a lot of time during the exam.
    - [Managing Kubernetes Objects Using Imperative Commands](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/imperative-command/)

### Zip through the docs
Not every resource can be created imperatively by kubectl.
Although you can access the k8s official docs during the exam, you will not have time to read everything.
Learn how to find manifests examples FAST. Search for keywords and once inside a doc page abuse Ctrl + F.

Example: You wanna remember how to create an StorageClass to solve an exam question.
1. Go to [the docs](https://kubernetes.io/docs/home/) and search for "storage class".
2. Once you've clicked on one of the relevant results, use `ctrl + F` and search further for `kind: Storage`.
That will highlight all the appearances of `kind: Storage`, decreasing the time needed to find an example `StorageClass` manifest.
4. Copy the example manifest to your vim/nano buffer and edit details as per the question instructions.

### Get comfortable on a CLI text editor
CLI text editors are much faster than clicking around on your IDE, but it won't matter if you can't quit `vim`.
Make sure you're comfortable editing yaml files on the cli. 
That includes:
- copying and pasting
- shifting and unshifting text columns (identation matters in yaml!)
- searching for and editing text
- saving and quitting
> The essential keybindings for `vim` and some extra tricks are covered in [this video](https://www.youtube.com/watch?v=TlyXfEpFvKI).
> Make sure to research how to perform those actions in your favorite CLI text editor, be it `nano`, `emacs` or something else.
