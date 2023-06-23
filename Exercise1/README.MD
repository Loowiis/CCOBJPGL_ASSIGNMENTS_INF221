public class Exercise1 {

    static boolean iwillNotCheat = false;
    static boolean iWillWin = false;

    public static void main(String[] args) {

        // Precondition
        assert iwillNotCheat == true : "I will never cheat";

        enterCompetition();

        // Postcondition
        assert iWillWin == true : "I will do everything and I know I can";

    }

    static void enterCompetition() {
        iWillWin = false;
    }

}
