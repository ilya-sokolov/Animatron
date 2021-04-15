# Sierpinski curve view #

Deriving the Sierpinski curve of a given order

[See](https://en.wikipedia.org/wiki/Sierpi%C5%84ski_curve)

![Sierpincki curve](/img/sierpincki.png)

**Example in layout:**

```xml
    <org.redbyte.animatron.trigan.SierpinskiCurveView
        android:id="@+id/scv"
        android:layout_width="0dp"
        android:layout_height="0dp"
        app:distance="420dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:level="6" />
```