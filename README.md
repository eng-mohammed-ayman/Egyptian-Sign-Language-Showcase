# Egyptian Sign Language Recognition

## Team graduation-project showcase, no source code

A Galala University AI engineering graduation project exploring Egyptian Sign Language gesture recognition and Arabic output. This repository documents Mohamed Ayman's contribution using materials from his own project archive. It is a documentation showcase, not a runnable application or an open-source release of the team's implementation.

## My contribution

Mohamed contributed to dataset preparation and refinement, initial research and technical documentation. He reviewed model comparisons and system results. He does not claim independent authorship of the trained model, inference engine or graphical interface.

## What the documented system does

The project materials describe a webcam-based pipeline:

1. Capture a gesture video sequence.
2. Extract pose and hand landmarks with MediaPipe Holistic.
3. Represent each frame with 75 three-dimensional landmarks, 225 features in total.
4. Process 30-frame sequences with a two-layer LSTM recognition model.
5. Map the predicted sign to an Arabic label for display, with text/speech output described in the project documentation.

The materials discuss several experimental approaches. This summary focuses on the landmark/LSTM path described in the approved contribution record, rather than merging every experiment into a claim about one deployed system.


## Team credits

The supplied graduation report credits Maryam Elgohary, Shahd Ahmed, Ahmed Ashraf, Mohamed Ibrahim and Mohamed Ayman, supervised by Dr. Mohamed Ghetas. The presentation uses a different form of Shahd's name, so the report form is retained here without guessing a correction.

## Original project materials

[Download the privacy-redacted 22-page presentation](materials/ESL-Presentation-Redacted.pdf). It retains the team-members slide, including Mohamed's name. Student IDs and all photographic signer screenshots are removed. The PDF is historical project evidence: its dataset counts, accuracy, novelty and application statements are original unverified slide claims, not new validated claims by this showcase. Read the limitations below before citing it.

[Download the privacy-redacted 53-page report](materials/ESL-Report-Redacted.pdf). Team names and all pages remain; student IDs and photographic signer images are removed. Its figures and experimental claims are historical and have not been independently reproduced.

## Evidence and limits

See [MATERIALS.md](MATERIALS.md) for the exact source materials used and what was intentionally left out.

- No source code, model weights, training data, private dataset records or implementation files are included.
- No independent live demo was present in the supplied folder. Presentation screenshots are historical illustrations, not proof of current availability.
- Dataset totals differ across the supplied materials, so this showcase does not advertise a dataset size or vocabulary count.
- Accuracy, latency/FPS, signer-independent evaluation and real-world deployment were not independently verified and are not advertised here.
- Intended applications in the slides are not evidence of deployment in healthcare, education or public services.
- This prototype should not be relied on for medical, legal, emergency or other high-stakes interpreting. Human review and broader evaluation would be required.

## Publication boundaries

This repository contains only original contribution-focused text grounded in the supplied archive. It does not link to or copy another team's repository, paper or implementation. It grants no new rights over team code, datasets or third-party material. No student IDs, signer photos or sample signer videos are republished. Privacy-redacted versions of the original report and presentation are included as team-membership and project-history evidence.
