## Бином Ньютона

$$(a + b)^n = \sum_{k=0}^{n} C_n^k \dot a^{n-k} \cdot b^k\,\space где \space C_n^k = \frac{n!}{k!(n-k)!} — биномиальные \space коэффициенты$$

# Задание №1

<img width="885" height="82" alt="image" src="https://github.com/user-attachments/assets/d53661ee-10af-4cbf-803f-45ad59a2796a" />

(x + 2)^4 = x^4 + 8x^3 + 24x^2 + 32x + 16

# Задание №2

<img width="742" height="69" alt="image" src="https://github.com/user-attachments/assets/05dc029b-8813-4a88-a85b-6bce1194859c" />

<img width="514" height="55" alt="image" src="https://github.com/user-attachments/assets/eda29801-fa7b-43bb-8c69-f8e3543604c1" />

Данного коэф. не существует, следовательно - 0

<img width="519" height="66" alt="image" src="https://github.com/user-attachments/assets/490ced67-0717-4a5f-a469-d32ebbdf5234" />

$$C_{13}^6 = \frac{13!}{6!(13-6)!} = \frac{13!}{6!7!} = 1716$$

# Задание №3

<img width="873" height="103" alt="image" src="https://github.com/user-attachments/assets/2fd78f94-d890-48c0-a1da-752a8ddc8c3a" />

4

# Задание №4

<img width="600" height="154" alt="image" src="https://github.com/user-attachments/assets/ff627dd8-77a3-4f74-8c02-97a5d5e3b54d" />

n = 3

$$C_{3}^0 = C_{3}^3 = 1$$

$$C_{3}^1 = C_{3}^2 = \frac{3!}{2!1!} = 3$$

$$ 1 + 3 + 3 + 1 = 8 = 2^n$$

$$ 1 - 3 + 3 - 1 = (-1)^n C_{n}^n = 0$$

# Задание №5

<img width="727" height="130" alt="image" src="https://github.com/user-attachments/assets/bfeb44c6-7df0-467e-baa4-319986a781a4" />

$$ 1 + 9 + 9 + 1 = C_{2n}^{n} = \frac{6!}{3!3!} = 20$$

## Неравенство Бернулли

$$(1 + x)^n \geq 1 + nx$$

# Задание №6

<img width="888" height="529" alt="image" src="https://github.com/user-attachments/assets/ca48bad0-eb43-471d-9754-2d9589d706f1" />

# Задание №7

<img width="881" height="94" alt="image" src="https://github.com/user-attachments/assets/97cf9fe4-d654-489c-9c39-183d8b21a275" />

$$ n = 1$$

$$ 1 + x \geq 1 + x $$

$$ n = 2$$

$$ (1 + x)^2 \geq 1 + 2x $$

$$ 1 + 2x + x^2 \geq 1 + 2x $$

$$ n = k + 1$$

$$ (1 + x)^{k + 1} > (1 + x)(1 + kx) > 1 + (k + 1)x $$

$$ (1 + x)^{k + 1} > 1 + x + xk + kx^2 > 1 + (k + 1)x $$

$$ (1 + x)^{k + 1} > 1 + (k + 1)x + kx^2 > 1 + (k + 1)x $$

# Задание №8

<img width="650" height="105" alt="image" src="https://github.com/user-attachments/assets/b373205e-6f99-443a-b214-84571185e42a" />

$$ (1 + \epsilon)^n = 1 + n\epsilon + C_n^{2}\epsilon^2 + \cdots + C_{n}^{n}\epsilon^n \geq 1 + n\epsilon + \frac{n(n - 1)}{2}\epsilon^2 > 1000n$$

$$ \frac{n^2}{2}\epsilon^2 + \frac{n}{2}\epsilon^2 + n\epsilon - 1000n + 1 > 0 $$

## Значение многочлена при больших x

$$ 1,001^n > 1000,\space n > 10^6 \sim n >> 0$$

$$ P(x) = a_kx^k + a_{k-1}x^{k-1} + \dots + a_1x + a_0, \space a_k > 0$$

$$ a_kx^k + a_{k-1}x^{k-1} + \dots + a_1x + a_0 > 0, \space x >> 0$$

$$ a_kx^k > -a_{k-1}x^{k-1} - \dots + a_1x - a_0$$

$$ x^k > b_{k-1}x^{k-1} - \cdots - b_1x - b_0$$

$$ b_{k-1}x^{k-1} - \cdots + b_1x - b_0 < |b_{k-1}|x^{k-1} - \dots + |b_1|x + |b_0|$$

$$ x^i < x^{k - 1}, \space x > 1$$

$$ |b_{k-1}|x^{k-1} - \dots + |b_1|x + |b_0| < |b_{k-1}|x^{k-1} - \dots + |b_1|x^{k-1} + |b_0|x^{k-1} $$

$$ |b_{k-1}|x^{k-1} - \dots + |b_1|x^{k-1} + |b_0|x^{k-1} = x^{k - 1}(|b_{k-1} - \dots + |b_1| + |b_0|)$$
