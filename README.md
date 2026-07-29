    }
}

int main() {
    string input;
    string fullMorse = "";
    
    cout << "Enter a message in English (A-Z characters only): ";
    getline(cin, input);
    
    cout << "Output Morse code:" << endl;
    
    for(int i = 0; i < input.length(); i++) {
        char c = toupper(input[i]); // convert to uppercase
        
        if(isalpha(c)) { // only process letters A-Z
            string code = getMorse(c);
