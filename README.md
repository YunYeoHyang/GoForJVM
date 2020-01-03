# GoForJVM
Use GoLand to Make JVM

# Package Project
go build

# Run test
{$GoForJvm.exe} -Xjre {$java/jre} {ClassName}

eg: className like java.lang.Object

# 2020.01.03
Now update project that you can know how does JVM where to find classFile, test for printing classData in terminal.
Next update for class analysis.

# 2020.01.03 2nd
Class analysis support.

The ClassFile structure is an intermediate layer added for the implementation class's function loading

In Future will transform ClassFile into Class structure,and put them into func-area.

But next update, will implement runtime data-area