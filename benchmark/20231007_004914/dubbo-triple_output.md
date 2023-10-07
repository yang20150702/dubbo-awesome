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
# Warmup Iteration   1: 2.043 ops/ms
# Warmup Iteration   2: 4.583 ops/ms
# Warmup Iteration   3: 8.038 ops/ms
Iteration   1: 8.761 ops/ms
Iteration   2: 8.964 ops/ms
Iteration   3: 9.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.929 ±(99.9%) 2.795 ops/ms [Average]
  (min, avg, max) = (8.761, 8.929, 9.061), stdev = 0.153
  CI (99.9%): [6.134, 11.723] (assumes normal distribution)


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
# Warmup Iteration   1: 2.867 ops/ms
# Warmup Iteration   2: 8.676 ops/ms
# Warmup Iteration   3: 9.195 ops/ms
Iteration   1: 9.408 ops/ms
Iteration   2: 9.433 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.477 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (9.408, 9.477, 9.590), stdev = 0.099
  CI (99.9%): [7.676, 11.278] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.474 ops/ms
# Warmup Iteration   2: 7.742 ops/ms
# Warmup Iteration   3: 9.248 ops/ms
Iteration   1: 8.806 ops/ms
Iteration   2: 9.032 ops/ms
Iteration   3: 8.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.941 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (8.806, 8.941, 9.032), stdev = 0.119
  CI (99.9%): [6.765, 11.117] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.604 ops/ms
# Warmup Iteration   2: 6.904 ops/ms
# Warmup Iteration   3: 7.323 ops/ms
Iteration   1: 7.417 ops/ms
Iteration   2: 7.428 ops/ms
Iteration   3: 7.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.429 ±(99.9%) 0.230 ops/ms [Average]
  (min, avg, max) = (7.417, 7.429, 7.442), stdev = 0.013
  CI (99.9%): [7.199, 7.659] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.552 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.004 ms/op
Iteration   1: 3.589 ±(99.9%) 0.007 ms/op
Iteration   2: 3.579 ±(99.9%) 0.006 ms/op
Iteration   3: 3.537 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.568 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.537, 3.568, 3.589), stdev = 0.027
  CI (99.9%): [3.068, 4.069] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.412 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.004 ms/op
Iteration   1: 3.391 ±(99.9%) 0.003 ms/op
Iteration   2: 3.348 ±(99.9%) 0.004 ms/op
Iteration   3: 3.406 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.382 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.348, 3.382, 3.406), stdev = 0.030
  CI (99.9%): [2.830, 3.933] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.548 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.005 ms/op
Iteration   1: 3.469 ±(99.9%) 0.006 ms/op
Iteration   2: 3.550 ±(99.9%) 0.003 ms/op
Iteration   3: 3.589 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.536 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.469, 3.536, 3.589), stdev = 0.061
  CI (99.9%): [2.422, 4.650] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.608 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.006 ms/op
Iteration   1: 4.313 ±(99.9%) 0.009 ms/op
Iteration   2: 4.248 ±(99.9%) 0.009 ms/op
Iteration   3: 4.216 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.259 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (4.216, 4.259, 4.313), stdev = 0.050
  CI (99.9%): [3.353, 5.165] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.484 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.013 ms/op
Iteration   1: 3.615 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  22.390 ms/op
                 createUser·p0.9999: 26.982 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 3.725 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  23.609 ms/op
                 createUser·p0.9999: 40.501 ms/op
                 createUser·p1.00:   41.157 ms/op

Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 27.451 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263805
  mean =      3.638 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 255011 
    [ 5.000, 10.000) = 8065 
    [10.000, 15.000) = 361 
    [15.000, 20.000) = 48 
    [20.000, 25.000) = 190 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.987 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     39.050 ms/op
     p(99.9990) =     41.157 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.238 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.009 ms/op
Iteration   1: 3.492 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 19.459 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  19.565 ms/op
                 existUser·p0.9999: 23.037 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  14.491 ms/op
                 existUser·p0.9999: 25.478 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273388
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6308 
    [ 2.500,  5.000) = 257357 
    [ 5.000,  7.500) = 8069 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     23.811 ms/op
     p(99.9990) =     25.970 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.501 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.015 ms/op
Iteration   1: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.544 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  15.545 ms/op
                 getUser·p0.9999: 25.723 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  20.952 ms/op
                 getUser·p0.9999: 27.517 ms/op
                 getUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271863
  mean =      3.531 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1775 
    [ 2.500,  5.000) = 261741 
    [ 5.000,  7.500) = 6883 
    [ 7.500, 10.000) = 897 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     19.796 ms/op
     p(99.9900) =     26.720 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.346 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.015 ms/op
Iteration   1: 4.302 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 21.533 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 4.318 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.193 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 224635
  mean =      4.270 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 211362 
    [ 5.000,  7.500) = 9575 
    [ 7.500, 10.000) = 2660 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.929 ± 2.795  ops/ms
ClientPb.existUser                       thrpt       3   9.477 ± 1.801  ops/ms
ClientPb.getUser                         thrpt       3   8.941 ± 2.176  ops/ms
ClientPb.listUser                        thrpt       3   7.429 ± 0.230  ops/ms
ClientPb.createUser                       avgt       3   3.568 ± 0.500   ms/op
ClientPb.existUser                        avgt       3   3.382 ± 0.552   ms/op
ClientPb.getUser                          avgt       3   3.536 ± 1.114   ms/op
ClientPb.listUser                         avgt       3   4.259 ± 0.906   ms/op
ClientPb.createUser                     sample  263805   3.638 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.374           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.987           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.050           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.157           ms/op
ClientPb.existUser                      sample  273388   3.508 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.262           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.629           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.811           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  271863   3.531 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.770           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.796           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.720           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.475           ms/op
ClientPb.listUser                       sample  224635   4.270 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.170           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.135           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.413           ms/op
