```mermaid
flowchart TD
A[Start] --> B{Generate Random Number} B --> C[Input Guess from User] C --> D{Is Input Between 1 and 5?} D --> |No| E[Display 'Invalid Input' Message] --> F[End] D --> |Yes| G{Is Guess Correct?} G --> |Yes| H[Display 'Correct Guess' Message] G --> |No| I{"Higher or Lower?"} I --> |Higher| J[Display 'Too High' Message] I --> |Lower| K[Display 'Too Low' Message] J --> C K --> C H --> L[End]
