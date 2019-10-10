## ![slides/img/logo_green.svg](slides/img/logo_green.svg) <!-- .element: style="border: none; box-shadow: none; width: 40%;" -->

---

- +300K Строк кода
- +1.2K React компонентов
- Flow `all=true`

---

```
// ResumeExperienceEntityType.js
type Identity = BaseEntityOfType<'resumeExperience'>;

type Attributes = {|
  position: string,
  dateStart: string,
  dateEnd: string | null,
|};

type Relations = {|
  resumeCompany?: ResumeExperienceCompanyEntityType,
|};

export type ResumeExperienceEntityType =
  Entity<Identity, Attributes, Relations>;
```
