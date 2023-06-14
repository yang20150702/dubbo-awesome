# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.482 ops/ms
# Warmup Iteration   2: 3.222 ops/ms
# Warmup Iteration   3: 6.572 ops/ms
Iteration   1: 6.851 ops/ms
Iteration   2: 7.668 ops/ms
Iteration   3: 7.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.370 ±(99.9%) 8.222 ops/ms [Average]
  (min, avg, max) = (6.851, 7.370, 7.668), stdev = 0.451
  CI (99.9%): [≈ 0, 15.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.034 ops/ms
# Warmup Iteration   2: 6.130 ops/ms
# Warmup Iteration   3: 7.754 ops/ms
Iteration   1: 8.202 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.188 ±(99.9%) 0.445 ops/ms [Average]
  (min, avg, max) = (8.160, 8.188, 8.203), stdev = 0.024
  CI (99.9%): [7.743, 8.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.172 ops/ms
# Warmup Iteration   2: 6.639 ops/ms
# Warmup Iteration   3: 7.746 ops/ms
Iteration   1: 7.457 ops/ms
Iteration   2: 7.477 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.668 ±(99.9%) 6.359 ops/ms [Average]
  (min, avg, max) = (7.457, 7.668, 8.071), stdev = 0.349
  CI (99.9%): [1.309, 14.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.005 ops/ms
# Warmup Iteration   2: 5.286 ops/ms
# Warmup Iteration   3: 6.376 ops/ms
Iteration   1: 6.200 ops/ms
Iteration   2: 6.602 ops/ms
Iteration   3: 6.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.479 ±(99.9%) 4.420 ops/ms [Average]
  (min, avg, max) = (6.200, 6.479, 6.635), stdev = 0.242
  CI (99.9%): [2.058, 10.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.568 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.358 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.009 ms/op
Iteration   1: 4.054 ±(99.9%) 0.015 ms/op
Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
Iteration   3: 3.921 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.987 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (3.921, 3.987, 4.054), stdev = 0.067
  CI (99.9%): [2.773, 5.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.171 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.894 ±(99.9%) 0.003 ms/op
Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
Iteration   3: 3.891 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.896 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.891, 3.896, 3.903), stdev = 0.006
  CI (99.9%): [3.778, 4.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.693 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.007 ms/op
Iteration   1: 4.056 ±(99.9%) 0.005 ms/op
Iteration   2: 4.105 ±(99.9%) 0.005 ms/op
Iteration   3: 4.034 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.065 ±(99.9%) 0.664 ms/op [Average]
  (min, avg, max) = (4.034, 4.065, 4.105), stdev = 0.036
  CI (99.9%): [3.401, 4.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.753 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.646 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.925 ±(99.9%) 0.007 ms/op
Iteration   1: 4.867 ±(99.9%) 0.010 ms/op
Iteration   2: 4.973 ±(99.9%) 0.008 ms/op
Iteration   3: 4.731 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.857 ±(99.9%) 2.214 ms/op [Average]
  (min, avg, max) = (4.731, 4.857, 4.973), stdev = 0.121
  CI (99.9%): [2.643, 7.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.676 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.937 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.020 ms/op
Iteration   1: 4.144 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.911 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  24.656 ms/op
                 createUser·p0.9999: 29.664 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.299 ms/op
                 createUser·p0.999:  14.538 ms/op
                 createUser·p0.9999: 29.627 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   3: 4.328 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.925 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.047 ms/op
                 createUser·p0.999:  30.253 ms/op
                 createUser·p0.9999: 34.844 ms/op
                 createUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229822
  mean =      4.177 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 228 
    [ 2.500,  5.000) = 211653 
    [ 5.000,  7.500) = 14809 
    [ 7.500, 10.000) = 2408 
    [10.000, 12.500) = 371 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.781 ms/op
     p(99.9000) =     24.942 ms/op
     p(99.9900) =     33.292 ms/op
     p(99.9990) =     35.515 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.390 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 4.995 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.015 ms/op
Iteration   1: 4.436 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.693 ms/op
                 existUser·p0.99:   10.157 ms/op
                 existUser·p0.999:  16.319 ms/op
                 existUser·p0.9999: 29.326 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   2: 3.996 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   5.174 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  18.511 ms/op
                 existUser·p0.9999: 28.704 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 4.065 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  13.620 ms/op
                 existUser·p0.9999: 31.483 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230872
  mean =      4.157 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 172 
    [ 2.500,  5.000) = 210114 
    [ 5.000,  7.500) = 16014 
    [ 7.500, 10.000) = 3118 
    [10.000, 12.500) = 806 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.885 ms/op
     p(99.9000) =     17.932 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     32.060 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.844 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.015 ms/op
Iteration   1: 4.040 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 28.351 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   2: 4.332 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.048 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   6.562 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  25.723 ms/op
                 getUser·p0.9999: 33.792 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 4.050 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.873 ms/op
                 getUser·p0.999:  14.060 ms/op
                 getUser·p0.9999: 32.385 ms/op
                 getUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232074
  mean =      4.136 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 213476 
    [ 5.000,  7.500) = 14007 
    [ 7.500, 10.000) = 3342 
    [10.000, 12.500) = 640 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     23.033 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     34.870 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.025 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 6.270 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.327 ±(99.9%) 0.024 ms/op
Iteration   1: 4.869 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  26.452 ms/op
                 listUser·p0.9999: 29.926 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   2: 5.096 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   10.054 ms/op
                 listUser·p0.999:  22.538 ms/op
                 listUser·p0.9999: 26.926 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   3: 4.791 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 20.555 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195189
  mean =      4.915 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 152562 
    [ 5.000,  7.500) = 36400 
    [ 7.500, 10.000) = 4611 
    [10.000, 12.500) = 867 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.370 ± 8.222  ops/ms
ClientPb.existUser                       thrpt       3   8.188 ± 0.445  ops/ms
ClientPb.getUser                         thrpt       3   7.668 ± 6.359  ops/ms
ClientPb.listUser                        thrpt       3   6.479 ± 4.420  ops/ms
ClientPb.createUser                       avgt       3   3.987 ± 1.214   ms/op
ClientPb.existUser                        avgt       3   3.896 ± 0.118   ms/op
ClientPb.getUser                          avgt       3   4.065 ± 0.664   ms/op
ClientPb.listUser                         avgt       3   4.857 ± 2.214   ms/op
ClientPb.createUser                     sample  229822   4.177 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.781           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.942           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.292           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.652           ms/op
ClientPb.existUser                      sample  230872   4.157 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.571           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.885           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.932           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.802           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  232074   4.136 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.827           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.915           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.487           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.033           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.260           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  195189   4.915 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.955           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.545           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.692           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.295           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.425           ms/op
