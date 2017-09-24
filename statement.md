# Welcome!

This Java template lets you get started quickly with a simple one-page playground.

```java runnable

public enum Singleton {

	INSTANCE;

	public void doProcess() {
		System.out.println("Do high memory or CPU consume operation.");
	}

}

class Main {

	public static void main(String[] args) {
		Singleton.INSTANCE.doProcess();
	}
}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Java template](https://tech.io/select-repo/385)
