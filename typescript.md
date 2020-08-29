## Home Page <!-- {docsify-ignore} -->
[Home](README.md)
# Typescript
_starting_
## Utility Types
### Record<Keys, Type>
```typescript
interface PageInfo {
    title: string;
}

type Page = 'home' | 'about' | 'contact'

const strictModel: Record<Page, PageInfo> = {
  about: { title: 'about' },
  contact: { title: 'contact' },
  home: { title: 'home' },
};

const looseKey: Record<string, PageInfo> = {
  anyKey: { title: 'about' }
};

const looseValueType: Record<Page, string| ''> = {
  about: 'I',
  contact: 'have to give',
  home: 'all Keys'
};

const looseTypeAndOptionalKeys: Partial<Record<Page, string| ''>> = {
  contact: 'I don\'t have to give',
  home: 'all Keys'
};
```

Last Updated: {docsify-updated}  
