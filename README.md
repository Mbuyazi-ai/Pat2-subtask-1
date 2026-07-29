           cout << c << ": " << code << endl;
            
            // build full message
            if(!fullMorse.empty()) {
                fullMorse += " "; // three spaces between letters
            }
            fullMorse += code;
        }
    }
    
    cout << endl << "Full Morse Code Message: " << fullMorse << endl;
    
    return 0;
}
