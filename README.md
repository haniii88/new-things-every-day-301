from datetime import datetime
import rando

def new_things_every_day_30():
    now = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    message = random.choice([
        "Daily coding builds unstoppable habits.",
        "Every commit is a victory — make one today!",
        "Small steps every day lead to big success.",
        "One more day, one more line, one more win.",
        "Consistency is your strongest tool — use it."
    ])
    print(f"[#30] {message} — {now}")

if __name__ == "__main__":
    new_things_every_day_30()
