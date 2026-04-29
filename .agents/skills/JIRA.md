# JIRA Ticket Skill

Follow these instructions whenever asked to create a Jira ticket.

## Ticket Type Selection

- **Default**: Always create a **Story** when asked to create a ticket.
- **Exceptions**: Create a **Bug** or **Epic** only if explicitly requested.

## General Metadata

- **Labels**: Always apply the following labels: `Core`, `Auto`.

---

## Ticket Templates

### 1. Story / Task
**Title Format**: `[{Label}] {Title}` (Use `Core` or `Auto` as the label in the title)

**Description Template**:
```markdown
## Background

## Details

## Acceptance criteria
```

### 2. Bug
**Description Template**:
```markdown
## Background

## Details

## Acceptance criteria

## Steps to reproduce
```

### 3. Epic
**Description Template**:
(Provide a simple 3-4 line description. Avoid sections.)
