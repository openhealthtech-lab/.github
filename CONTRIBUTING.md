# Contributing

Thanks for your interest in Open HealthTech Collab Lab! We welcome contributions from students, educators, researchers and clinicians.

## Ways to contribute

- **Report a problem**: a broken notebook, a wrong instruction or an outdated link
- **Suggest a project idea**: a real problem that could become a student or research project
- **Propose a collaboration**: academia, research centres and hospitals are welcome
- **Improve teaching material**: clearer explanations, exercises or translations
- **Submit code**: fixes, new examples or new labs

Use the issue templates when you open an issue. They ask for the information we need.

## Making a change

1. Fork the repo and create a branch with a short descriptive name, e.g. `fix-brats-dataloader`.
2. Make your change. Keep each pull request focused on one thing.
3. Check that notebooks run from top to bottom on a clean environment (Google Colab is fine).
4. Clear notebook outputs that contain large images or any data you are not allowed to share.
5. Open a pull request and fill in the template.

## Data rules

These rules protect patients and our partners. They are not optional.

- **Never commit patient data** or anything that could identify a person, including DICOM headers with names, IDs or dates.
- Use **public, de-identified datasets** and state the dataset's name and license.
- Data from partner organizations stays outside these repos unless a written agreement allows otherwise.

## Licensing

- Respect the license of every project and dataset you use.
- By contributing, you agree that your contribution is released under the license of the repo you contribute to.

## Code style

- Python: follow PEP 8, and keep functions short with clear names.
- Pin library versions in `requirements.txt`.
- Write comments and lab instructions for students: plain words, one step at a time.

## Questions

See [SUPPORT.md](SUPPORT.md).
