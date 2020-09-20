## Shamil Tadtaev

### Contacts
- __Skype__: shamilft
- __Email__: shtadtaev@gmail.com

### Summary
I want to improve my skills in web development.

### Skills
React, TypeScript, JS, HTML, CSS, C#, .Net...

### Code example
```typescript
/**
 * Преобразовывает число в формат с плавающей точкой для отображения финансовых показателей.
 * @param {number} number Число
 * @param {number} digits Количество цифр, которые надо отобразить после запятой
 */
export const financial = (
	number: number,
	digits: number = 3
): string | null => {
	if (!Number.isFinite(number)) return null;
	return new Intl.NumberFormat('ru-RU', {
		minimumFractionDigits: digits,
	}).format(number);
};
```

### Education
Moscow Power Engineering Institute

### English
B2
