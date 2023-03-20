# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 5.540 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 9.169 ops/ms
Iteration   2: 9.079 ops/ms
Iteration   3: 9.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.119 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (9.079, 9.119, 9.169), stdev = 0.046
  CI (99.9%): [8.278, 9.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 8.800 ops/ms
# Warmup Iteration   3: 8.996 ops/ms
Iteration   1: 9.823 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.542 ±(99.9%) 4.912 ops/ms [Average]
  (min, avg, max) = (9.286, 9.542, 9.823), stdev = 0.269
  CI (99.9%): [4.630, 14.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.359 ops/ms
# Warmup Iteration   2: 8.519 ops/ms
# Warmup Iteration   3: 9.181 ops/ms
Iteration   1: 9.170 ops/ms
Iteration   2: 9.202 ops/ms
Iteration   3: 9.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.160 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (9.107, 9.160, 9.202), stdev = 0.048
  CI (99.9%): [8.278, 10.042] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.932 ops/ms
# Warmup Iteration   2: 7.243 ops/ms
# Warmup Iteration   3: 8.038 ops/ms
Iteration   1: 7.596 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 8.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.968 ±(99.9%) 5.939 ops/ms [Average]
  (min, avg, max) = (7.596, 7.968, 8.199), stdev = 0.326
  CI (99.9%): [2.029, 13.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.542 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.005 ms/op
Iteration   1: 3.287 ±(99.9%) 0.011 ms/op
Iteration   2: 3.441 ±(99.9%) 0.007 ms/op
Iteration   3: 3.520 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.416 ±(99.9%) 2.157 ms/op [Average]
  (min, avg, max) = (3.287, 3.416, 3.520), stdev = 0.118
  CI (99.9%): [1.259, 5.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.986 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.006 ms/op
Iteration   1: 3.456 ±(99.9%) 0.008 ms/op
Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
Iteration   3: 3.293 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.248, 3.333, 3.456), stdev = 0.109
  CI (99.9%): [1.335, 5.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.188 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
Iteration   1: 3.417 ±(99.9%) 0.006 ms/op
Iteration   2: 3.327 ±(99.9%) 0.007 ms/op
Iteration   3: 3.386 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.377 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.327, 3.377, 3.417), stdev = 0.046
  CI (99.9%): [2.542, 4.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.115 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.014 ms/op
Iteration   1: 3.924 ±(99.9%) 0.013 ms/op
Iteration   2: 3.962 ±(99.9%) 0.016 ms/op
Iteration   3: 3.897 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.927 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (3.897, 3.927, 3.962), stdev = 0.032
  CI (99.9%): [3.335, 4.519] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.378 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.015 ms/op
Iteration   1: 3.341 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.114 ms/op
                 createUser·p0.999:  19.691 ms/op
                 createUser·p0.9999: 23.976 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.536 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  22.008 ms/op
                 createUser·p0.9999: 24.803 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.528 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  16.960 ms/op
                 createUser·p0.9999: 24.279 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276736
  mean =      3.466 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11702 
    [ 2.500,  5.000) = 258973 
    [ 5.000,  7.500) = 5164 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     17.343 ms/op
     p(99.9900) =     24.456 ms/op
     p(99.9990) =     25.370 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.812 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  9.082 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  10.773 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.780 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  9.611 ms/op
                 existUser·p0.9999: 26.256 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294543
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14109 
    [ 2.500,  5.000) = 275839 
    [ 5.000,  7.500) = 3788 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.041 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.018 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.011 ms/op
Iteration   1: 3.435 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  20.627 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  21.011 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  25.035 ms/op
                 getUser·p0.9999: 30.039 ms/op
                 getUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280397
  mean =      3.422 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7160 
    [ 2.500,  5.000) = 266159 
    [ 5.000,  7.500) = 6132 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     20.795 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     30.551 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.576 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.014 ms/op
Iteration   1: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  16.446 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 4.101 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 16.636 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 4.032 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 15.943 ms/op
                 listUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237371
  mean =      4.043 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 227063 
    [ 5.000,  7.500) = 7812 
    [ 7.500, 10.000) = 1703 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     23.291 ms/op
     p(99.9990) =     25.043 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.119 ± 0.840  ops/ms
ClientPb.existUser                       thrpt       3   9.542 ± 4.912  ops/ms
ClientPb.getUser                         thrpt       3   9.160 ± 0.882  ops/ms
ClientPb.listUser                        thrpt       3   7.968 ± 5.939  ops/ms
ClientPb.createUser                       avgt       3   3.416 ± 2.157   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 1.998   ms/op
ClientPb.getUser                          avgt       3   3.377 ± 0.835   ms/op
ClientPb.listUser                         avgt       3   3.927 ± 0.592   ms/op
ClientPb.createUser                     sample  276736   3.466 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.343           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.456           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.985           ms/op
ClientPb.existUser                      sample  294543   3.259 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.191           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.264           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  280397   3.422 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.026           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.884           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  237371   4.043 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.291           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
