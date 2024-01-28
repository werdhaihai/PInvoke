# CreateIoCompletionPort

```csharp
[DllImport("KERNEL32.dll", ExactSpelling = true, SetLastError = true)]
        public static extern IntPtr CreateIoCompletionPort(
            IntPtr FileHandle,
            [Optional] IntPtr ExistingCompletionPort,
            IntPtr CompletionKey,
            int NumberOfConcurrentThreads
            ); 
```
