# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 11.703 ops/ms
# Warmup Iteration   3: 12.254 ops/ms
Iteration   1: 12.472 ops/ms
Iteration   2: 12.471 ops/ms
Iteration   3: 12.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.464 ±(99.9%) 0.229 ops/ms [Average]
  (min, avg, max) = (12.450, 12.464, 12.472), stdev = 0.013
  CI (99.9%): [12.235, 12.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.383 ops/ms
# Warmup Iteration   2: 12.989 ops/ms
# Warmup Iteration   3: 12.850 ops/ms
Iteration   1: 13.030 ops/ms
Iteration   2: 12.909 ops/ms
Iteration   3: 12.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.948 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (12.906, 12.948, 13.030), stdev = 0.071
  CI (99.9%): [11.656, 14.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.324 ops/ms
# Warmup Iteration   2: 12.450 ops/ms
# Warmup Iteration   3: 12.416 ops/ms
Iteration   1: 12.750 ops/ms
Iteration   2: 12.670 ops/ms
Iteration   3: 12.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.750 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (12.670, 12.750, 12.829), stdev = 0.080
  CI (99.9%): [11.296, 14.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.215 ops/ms
# Warmup Iteration   2: 10.418 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.619 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (10.552, 10.619, 10.653), stdev = 0.057
  CI (99.9%): [9.570, 11.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.040 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.003 ms/op
Iteration   1: 2.582 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.542 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.547 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (2.515, 2.547, 2.582), stdev = 0.033
  CI (99.9%): [1.938, 3.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.438, 2.452, 2.468), stdev = 0.015
  CI (99.9%): [2.180, 2.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.495, 2.499, 2.503), stdev = 0.004
  CI (99.9%): [2.422, 2.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
Iteration   3: 3.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.993, 3.001, 3.009), stdev = 0.008
  CI (99.9%): [2.853, 3.149] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.116 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.787 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.601 ±(99.9%) 0.006 ms/op
Iteration   1: 2.582 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.634 ms/op
                 createUser·p0.99:   4.570 ms/op
                 createUser·p0.999:  12.419 ms/op
                 createUser·p0.9999: 15.296 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   2: 2.529 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  11.469 ms/op
                 createUser·p0.9999: 13.949 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 2.560 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.764 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375146
  mean =      2.557 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 188075 
    [ 2.500,  3.750) = 171129 
    [ 3.750,  5.000) = 13129 
    [ 5.000,  6.250) = 1271 
    [ 6.250,  7.500) = 536 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 194 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     11.712 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     16.028 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.007 ms/op
Iteration   1: 2.511 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.346 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  8.710 ms/op
                 existUser·p0.9999: 16.917 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 2.637 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  14.312 ms/op
                 existUser·p0.9999: 19.510 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   3: 2.652 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.332 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 24.312 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 369146
  mean =      2.599 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184493 
    [ 2.500,  5.000) = 179017 
    [ 5.000,  7.500) = 4382 
    [ 7.500, 10.000) = 762 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.332 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     20.027 ms/op
     p(99.9990) =     24.954 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.669 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.825 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.753 ±(99.9%) 0.010 ms/op
Iteration   1: 2.561 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.739 ms/op
                 getUser·p0.9999: 15.943 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   2: 2.585 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.338 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.842 ms/op
                 getUser·p0.999:  11.676 ms/op
                 getUser·p0.9999: 19.637 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 2.574 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.406 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  10.220 ms/op
                 getUser·p0.9999: 17.517 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372736
  mean =      2.573 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184517 
    [ 2.500,  5.000) = 185569 
    [ 5.000,  7.500) = 2045 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     17.841 ms/op
     p(99.9990) =     20.423 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.031 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.011 ms/op
Iteration   1: 3.087 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.421 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.144 ms/op
                 listUser·p0.999:  10.306 ms/op
                 listUser·p0.9999: 13.919 ms/op
                 listUser·p1.00:   14.533 ms/op

Iteration   2: 3.086 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.070 ms/op
                 listUser·p0.999:  11.270 ms/op
                 listUser·p0.9999: 14.068 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.022 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.322 ms/op
                 listUser·p0.9999: 13.615 ms/op
                 listUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312939
  mean =      3.065 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 438 
    [ 1.250,  2.500) = 103366 
    [ 2.500,  3.750) = 152390 
    [ 3.750,  5.000) = 46188 
    [ 5.000,  6.250) = 8123 
    [ 6.250,  7.500) = 1260 
    [ 7.500,  8.750) = 413 
    [ 8.750, 10.000) = 293 
    [10.000, 11.250) = 245 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     13.851 ms/op
     p(99.9990) =     14.852 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.464 ± 0.229  ops/ms
ClientPb.existUser                       thrpt       3  12.948 ± 1.292  ops/ms
ClientPb.getUser                         thrpt       3  12.750 ± 1.454  ops/ms
ClientPb.listUser                        thrpt       3  10.619 ± 1.049  ops/ms
ClientPb.createUser                       avgt       3   2.547 ± 0.608   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.271   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.077   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.148   ms/op
ClientPb.createUser                     sample  375146   2.557 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.690           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.499           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.712           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.385           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.777           ms/op
ClientPb.existUser                      sample  369146   2.599 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.332           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.436           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.027           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  372736   2.573 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.338           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.945           ms/op
ClientPb.getUser:getUser·p0.9999        sample          17.841           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.184           ms/op
ClientPb.listUser                       sample  312939   3.065 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.715           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.851           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.876           ms/op
