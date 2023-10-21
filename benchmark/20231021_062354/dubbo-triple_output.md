# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.925 ops/ms
# Warmup Iteration   2: 5.149 ops/ms
# Warmup Iteration   3: 8.531 ops/ms
Iteration   1: 9.017 ops/ms
Iteration   2: 9.014 ops/ms
Iteration   3: 9.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.016 ±(99.9%) 0.033 ops/ms [Average]
  (min, avg, max) = (9.014, 9.016, 9.017), stdev = 0.002
  CI (99.9%): [8.983, 9.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 9.085 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 9.728 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.802 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (9.728, 9.802, 9.869), stdev = 0.071
  CI (99.9%): [8.510, 11.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.783 ops/ms
# Warmup Iteration   2: 8.591 ops/ms
# Warmup Iteration   3: 9.110 ops/ms
Iteration   1: 9.254 ops/ms
Iteration   2: 9.415 ops/ms
Iteration   3: 9.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.291 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (9.203, 9.291, 9.415), stdev = 0.111
  CI (99.9%): [7.272, 11.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 7.340 ops/ms
# Warmup Iteration   3: 7.651 ops/ms
Iteration   1: 7.624 ops/ms
Iteration   2: 7.759 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.725 ±(99.9%) 1.623 ops/ms [Average]
  (min, avg, max) = (7.624, 7.725, 7.792), stdev = 0.089
  CI (99.9%): [6.103, 9.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.591 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.004 ms/op
Iteration   1: 3.508 ±(99.9%) 0.003 ms/op
Iteration   2: 3.451 ±(99.9%) 0.004 ms/op
Iteration   3: 3.376 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.445 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (3.376, 3.445, 3.508), stdev = 0.066
  CI (99.9%): [2.242, 4.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.105 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.008 ms/op
Iteration   1: 3.396 ±(99.9%) 0.003 ms/op
Iteration   2: 3.270 ±(99.9%) 0.005 ms/op
Iteration   3: 3.310 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.325 ±(99.9%) 1.174 ms/op [Average]
  (min, avg, max) = (3.270, 3.325, 3.396), stdev = 0.064
  CI (99.9%): [2.151, 4.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.680 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.003 ms/op
Iteration   1: 3.392 ±(99.9%) 0.003 ms/op
Iteration   2: 3.487 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.438 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.392, 3.438, 3.487), stdev = 0.048
  CI (99.9%): [2.566, 4.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.574 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.007 ms/op
Iteration   1: 4.216 ±(99.9%) 0.008 ms/op
Iteration   2: 4.085 ±(99.9%) 0.005 ms/op
Iteration   3: 4.011 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.104 ±(99.9%) 1.897 ms/op [Average]
  (min, avg, max) = (4.011, 4.104, 4.216), stdev = 0.104
  CI (99.9%): [2.207, 6.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.078 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.009 ms/op
Iteration   1: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  20.984 ms/op
                 createUser·p0.9999: 23.912 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  21.992 ms/op
                 createUser·p0.9999: 25.689 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.419 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  17.370 ms/op
                 createUser·p0.9999: 25.599 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276712
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9223 
    [ 2.500,  5.000) = 262201 
    [ 5.000,  7.500) = 4220 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     25.308 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.387 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
Iteration   1: 3.352 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  8.614 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.416 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  23.072 ms/op
                 existUser·p0.9999: 26.583 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  20.220 ms/op
                 existUser·p0.9999: 26.865 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284623
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2422 
    [ 2.500,  5.000) = 277442 
    [ 5.000,  7.500) = 3886 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.012 ms/op
Iteration   1: 3.484 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 23.745 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.536 ms/op
                 getUser·p0.999:  22.713 ms/op
                 getUser·p0.9999: 26.020 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  19.693 ms/op
                 getUser·p0.9999: 26.503 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277560
  mean =      3.456 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2459 
    [ 2.500,  5.000) = 269515 
    [ 5.000,  7.500) = 4442 
    [ 7.500, 10.000) = 561 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     19.413 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.671 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.719 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.011 ms/op
Iteration   1: 4.122 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.288 ms/op
                 listUser·p0.999:  20.263 ms/op
                 listUser·p0.9999: 25.141 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 4.093 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.036 ms/op
                 listUser·p0.9999: 17.078 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 4.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.013 ms/op
                 listUser·p0.9999: 15.583 ms/op
                 listUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234642
  mean =      4.091 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 226692 
    [ 5.000,  7.500) = 5841 
    [ 7.500, 10.000) = 1299 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     25.933 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.016 ± 0.033  ops/ms
ClientPb.existUser                       thrpt       3   9.802 ± 1.292  ops/ms
ClientPb.getUser                         thrpt       3   9.291 ± 2.019  ops/ms
ClientPb.listUser                        thrpt       3   7.725 ± 1.623  ops/ms
ClientPb.createUser                       avgt       3   3.445 ± 1.203   ms/op
ClientPb.existUser                        avgt       3   3.325 ± 1.174   ms/op
ClientPb.getUser                          avgt       3   3.438 ± 0.872   ms/op
ClientPb.listUser                         avgt       3   4.104 ± 1.897   ms/op
ClientPb.createUser                     sample  276712   3.468 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.608           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.579           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.308           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.623           ms/op
ClientPb.existUser                      sample  284623   3.368 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.507           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.378           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  277560   3.456 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.413           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.820           ms/op
ClientPb.listUser                       sample  234642   4.091 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.035           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.888           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
