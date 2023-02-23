# Installations
## Supabase SDK
`npm install @supabase/supabase-js`

# React
## Hooks
- Reactive components
  - Hooks
    - Replaced classes
    - Removes reactivity from components
    - State
    - Rules
      - Only call at top level of functional components except when using custom hooks
    - Types
      - useState
        - Update UI when state changes
        - returns const [Reactive Value, Setter]
      - useEffect
        - Run initially and when state changes
      - useContext
        - Share data without passing props
      - useReducer
        - Returns state and function that can dispatch actions
      - useMemo
        - Cache results when there is a complex calculation
      - useCallback
      - useRef
      - useImperativeHandle
      - useLayoutEffect
        - Run after render but before printing to screen
      - useDebugValue
# Supabase
- BaaS (Backend as a Service)

# Process
## Frontend
- I needed to use yarn instead of npm for vite because the drive I am using has an & in the path and npm cannot handle that
- Video said that "Type: Module" from package.json was causing an error with playwright

## Supabase CLI
- `yarn add -D supabase`
  - For right now this needs to be run twice
- `npx supabase --help`

## Playwright
- yarn create playwright