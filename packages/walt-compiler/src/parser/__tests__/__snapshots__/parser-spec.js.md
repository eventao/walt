# Snapshot report for `src/parser/__tests__/parser-spec.js`

The actual snapshot is saved in `parser-spec.js.snap`.

Generated by [AVA](https://ava.li).

## compiles exports

> Snapshot 1

    {
      Type: 'Program',
      meta: {},
      params: [
        {
          Type: 'Export',
          meta: {},
          params: [
            {
              Type: 'ImmutableDeclaration',
              meta: {},
              params: [
                {
                  Type: 'Constant',
                  meta: {},
                  params: [],
                  range: [
                    {
                      col: 30,
                      line: 1,
                      sourceLine: 'export const answer: i32 = 42;',
                    },
                    {
                      col: 30,
                      line: 1,
                      sourceLine: 'export const answer: i32 = 42;',
                    },
                  ],
                  toString: Function toString {},
                  type: 'i32',
                  value: '42',
                },
              ],
              range: [
                {
                  col: 31,
                  line: 1,
                  sourceLine: 'export const answer: i32 = 42;',
                },
                {
                  col: 30,
                  line: 1,
                  sourceLine: 'export const answer: i32 = 42;',
                },
              ],
              toString: Function toString {},
              type: 'i32',
              value: 'answer',
            },
          ],
          range: [
            {
              col: 31,
              line: 1,
              sourceLine: 'export const answer: i32 = 42;',
            },
            {
              col: 30,
              line: 1,
              sourceLine: 'export const answer: i32 = 42;',
            },
          ],
          toString: Function toString {},
          type: null,
          value: 'export',
        },
      ],
      range: [
        {
          col: 31,
          line: 1,
          sourceLine: 'export const answer: i32 = 42;',
        },
        {
          col: 30,
          line: 1,
          sourceLine: 'export const answer: i32 = 42;',
        },
      ],
      toString: Function toString {},
      type: null,
      value: 'ROOT_NODE',
    }

## compiles globals

> Snapshot 1

    {
      Type: 'Program',
      meta: {},
      params: [
        {
          Type: 'ImmutableDeclaration',
          meta: {},
          params: [
            {
              Type: 'Constant',
              meta: {},
              params: [],
              range: [
                {
                  col: 23,
                  line: 1,
                  sourceLine: 'const answer: i32 = 42;',
                },
                {
                  col: 23,
                  line: 1,
                  sourceLine: 'const answer: i32 = 42;',
                },
              ],
              toString: Function toString {},
              type: 'i32',
              value: '42',
            },
          ],
          range: [
            {
              col: 24,
              line: 1,
              sourceLine: 'const answer: i32 = 42;',
            },
            {
              col: 23,
              line: 1,
              sourceLine: 'const answer: i32 = 42;',
            },
          ],
          toString: Function toString {},
          type: 'i32',
          value: 'answer',
        },
      ],
      range: [
        {
          col: 24,
          line: 1,
          sourceLine: 'const answer: i32 = 42;',
        },
        {
          col: 23,
          line: 1,
          sourceLine: 'const answer: i32 = 42;',
        },
      ],
      toString: Function toString {},
      type: null,
      value: 'ROOT_NODE',
    }

## the most basic of modules in wasm

> Snapshot 1

    {
      Type: 'Program',
      meta: {},
      params: [],
      range: [
        {
          col: 1,
          line: 1,
          sourceLine: '',
        },
        {
          col: 10,
          line: 1,
          sourceLine: '',
        },
      ],
      toString: Function toString {},
      type: null,
      value: 'ROOT_NODE',
    }
