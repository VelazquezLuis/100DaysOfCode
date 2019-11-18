# 100DaysOfCode

let count = 0;
const H = "Hold";
const B = "Bet"

function cc(card) {
  switch (card) {
    case 2:
      console.log(H);
      break;
    case 3:
      console.log(H);
      break;  
    case 4:
      console.log(H);
      break;
    case 5:
      console.log(H);
      break;
    case 6:
      console.log(H);
      break;
    case 7:
      console.log(H);
      break;
    case 8:
      console.log(H);
      break;
    case 9:
      console.log(H);
      break; 
    case 9:
      console.log(H);
      break; 
    case 10:
        console.log(B);
        break;
    case 'J':
      console.log(B);
      break;
    case 'Q':
      console.log(B);
      break;
    case 'K':
      console.log(B);
      break;
    case 'A':
      console.log(B);
      break;
    default:
        console.log("test");
      break;
  }

  return "Change Me";
  // Only change code above this line
}

// Add/remove calls to test your function.
// Note: Only the last will display
cc(2);
cc(3);
cc(7);
cc("K");
cc("A");
