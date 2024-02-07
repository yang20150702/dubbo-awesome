# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.808 ops/ms
# Warmup Iteration   2: 12.033 ops/ms
# Warmup Iteration   3: 12.461 ops/ms
Iteration   1: 12.431 ops/ms
Iteration   2: 12.467 ops/ms
Iteration   3: 12.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.478 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (12.431, 12.478, 12.537), stdev = 0.054
  CI (99.9%): [11.492, 13.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.863 ops/ms
# Warmup Iteration   2: 12.829 ops/ms
# Warmup Iteration   3: 12.824 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.903 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 0.121 ops/ms [Average]
  (min, avg, max) = (12.900, 12.905, 12.913), stdev = 0.007
  CI (99.9%): [12.784, 13.026] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.648 ops/ms
# Warmup Iteration   2: 12.515 ops/ms
# Warmup Iteration   3: 12.547 ops/ms
Iteration   1: 12.732 ops/ms
Iteration   2: 12.926 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.810 ±(99.9%) 1.869 ops/ms [Average]
  (min, avg, max) = (12.732, 12.810, 12.926), stdev = 0.102
  CI (99.9%): [10.941, 14.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.742 ops/ms
# Warmup Iteration   2: 10.379 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.495 ops/ms
Iteration   3: 10.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.461 ±(99.9%) 1.004 ops/ms [Average]
  (min, avg, max) = (10.397, 10.461, 10.495), stdev = 0.055
  CI (99.9%): [9.457, 11.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.003 ms/op
Iteration   1: 2.562 ±(99.9%) 0.005 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.547 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.522, 2.547, 2.562), stdev = 0.021
  CI (99.9%): [2.158, 2.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.695 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.473 ±(99.9%) 0.003 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.473, 2.482, 2.491), stdev = 0.009
  CI (99.9%): [2.316, 2.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.479, 2.491, 2.500), stdev = 0.011
  CI (99.9%): [2.296, 2.685] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.727 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.006 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.034 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.031 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (3.026, 3.031, 3.035), stdev = 0.005
  CI (99.9%): [2.944, 3.119] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  12.161 ms/op
                 createUser·p0.9999: 14.085 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 14.163 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.525 ms/op
                 createUser·p0.9999: 10.823 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376150
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 179917 
    [ 2.500,  3.750) = 191939 
    [ 3.750,  5.000) = 3553 
    [ 5.000,  6.250) = 262 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.566 ms/op
     p(99.9900) =     13.853 ms/op
     p(99.9990) =     14.655 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  7.078 ms/op
                 existUser·p0.9999: 14.206 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  7.971 ms/op
                 existUser·p0.9999: 13.351 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390204
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 190844 
    [ 2.500,  3.750) = 196059 
    [ 3.750,  5.000) = 2485 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.976 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.488 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  9.684 ms/op
                 getUser·p0.9999: 13.798 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  9.335 ms/op
                 getUser·p0.9999: 12.917 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 18.789 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383526
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 187876 
    [ 2.500,  3.750) = 189687 
    [ 3.750,  5.000) = 4363 
    [ 5.000,  6.250) = 860 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      9.479 ms/op
     p(99.9900) =     14.068 ms/op
     p(99.9990) =     18.994 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.806 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.186 ms/op
                 listUser·p0.9999: 11.158 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 13.118 ms/op
                 listUser·p1.00:   13.369 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312676
  mean =      3.068 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 84356 
    [ 2.500,  3.750) = 185177 
    [ 3.750,  5.000) = 34930 
    [ 5.000,  6.250) = 6573 
    [ 6.250,  7.500) = 871 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.655 ms/op
     p(99.9900) =     12.020 ms/op
     p(99.9990) =     13.220 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.478 ± 0.986  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 0.121  ops/ms
ClientPb.getUser                         thrpt       3  12.810 ± 1.869  ops/ms
ClientPb.listUser                        thrpt       3  10.461 ± 1.004  ops/ms
ClientPb.createUser                       avgt       3   2.547 ± 0.389   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.166   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.195   ms/op
ClientPb.listUser                         avgt       3   3.031 ± 0.088   ms/op
ClientPb.createUser                     sample  376150   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.725           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.566           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  390204   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  383526   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.836           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.479           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.068           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.497           ms/op
ClientPb.listUser                       sample  312676   3.068 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.760           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.655           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.020           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.369           ms/op
