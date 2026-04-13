public class HelloArgs {
    public static void main(String[] args) {

        String result = "";

        // Combine all arguments with space
        for (int i = 0; i < args.length; i++) {
            result += args[i] + " ";
        }

        // Remove trailing space using substring
        if (result.length() > 0) {
            result = result.substring(0, result.length() - 1);
        }

        // Display output
        System.out.println("Hello " + result);
    }
}
