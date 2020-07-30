# TSF Wrapper

C# wrapper for Windows Text Service Framework.

# Why

Windows have two IME framework:, one is IMM (imm32.dll), which is the old one; another is TSF (msctf.dll), which was introduced in Windows XP.

Everything is fine when you use IMM to get text input from IME software in Win 7 and before.

But when it comes to Win8 or Win10, use IMM to get text input is buggy. To fix that, we have to use TSF to activate IME instead of IMM.
