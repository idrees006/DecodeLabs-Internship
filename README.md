import sys

def main():
    # Introduction and Setup
    print("====================================================")
    print("🤖 DEC0DE_BOT v1.0 | Rule-Based AI Chatbot initialized.")
    print("Status: Online | Type 'exit' or 'quit' to end session.")
    print("====================================================\n")
    
    # 1. Continuous Loop Requirement
    while True:
        try:
            # Capture user input and normalize it (lowercase & stripped spaces)
            user_input = input("You: ").strip().lower()
            
            # Catch empty inputs gracefully
            if not user_input:
                print("Dec0deBot: ...Hello? Is anyone there? 🤔")
                continue
                
            # 2. Exit Commands Requirement
            if user_input in ['exit', 'quit', 'goodbye', 'bye']:
                print("\nDec0deBot: Terminating continuous loop... Task complete! Goodbye! 🚀")
                print("====================================================")
                break
                
            # 3. Explicit If-Else Logic & Greetings Requirement
            elif user_input in ['hello', 'hi', 'hey', 'greetings']:
                print("Dec0deBot: Greetings, engineer! Welcome to the team. How can I assist you today? 💻")
                
            elif "help" in user_input or "what can you do" in user_input:
                print("Dec0deBot: I am programmed to demonstrate explicit control flow logic. You can ask me:")
                print("           -> 'About your project'")
                print("           -> 'What are your skills?'")
                print("           -> 'Who built you?'")
                
            elif "project" in user_input:
                # Nested Condition for smarter responses (Bonus Milestone)
                print("Dec0deBot: This is Project 1: The Rule-Based AI Chatbot for the DecodeLabs internship! 🛡️")
                follow_up = input("Dec0deBot: Would you like to know the qualification criteria? (yes/no): ").strip().lower()
                if follow_up == 'yes':
                    print("Dec0deBot: Excellent! You must complete this project to unlock next week's assignments. 🔑")
                else:
                    print("Dec0deBot: No problem. Back to the main stream.")
                    
            elif "skills" in user_input or "logic" in user_input:
                print("Dec0deBot: I simulate human interaction using continuous logic blocks, handling basic AI inputs! 🧠")
                
            elif "creator" in user_input or "built you" in user_input or "decodelabs" in user_input:
                print("Dec0deBot: I was architected by an AI Engineering Intern at DecodeLabs (Batch 2026)! 🚀")
                
            # Fallback condition for unrecognized vocabulary
            else:
                print("Dec0deBot: Error 404: Input unrecognized. My vocabulary is limited to my if-else rules! Try asking 'help'. 🧩")
                
        except (KeyboardInterrupt, SystemExit):
            print("\n\nDec0deBot: Unexpected interruption detected. Safely powering down. Bye!")
            sys.exit()

if __name__ == "__main__":
    main()
