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
# Warmup Iteration   1: 4.764 ops/ms
# Warmup Iteration   2: 11.744 ops/ms
# Warmup Iteration   3: 12.124 ops/ms
Iteration   1: 12.497 ops/ms
Iteration   2: 12.448 ops/ms
Iteration   3: 12.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.505 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (12.448, 12.505, 12.570), stdev = 0.061
  CI (99.9%): [11.388, 13.622] (assumes normal distribution)


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
# Warmup Iteration   1: 7.304 ops/ms
# Warmup Iteration   2: 12.891 ops/ms
# Warmup Iteration   3: 12.922 ops/ms
Iteration   1: 12.933 ops/ms
Iteration   2: 12.972 ops/ms
Iteration   3: 13.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.981 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (12.933, 12.981, 13.038), stdev = 0.053
  CI (99.9%): [12.014, 13.948] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.535 ops/ms
# Warmup Iteration   2: 12.471 ops/ms
# Warmup Iteration   3: 12.632 ops/ms
Iteration   1: 12.646 ops/ms
Iteration   2: 12.768 ops/ms
Iteration   3: 12.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.705 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (12.646, 12.705, 12.768), stdev = 0.061
  CI (99.9%): [11.591, 13.819] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.564 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.525 ops/ms
Iteration   1: 10.587 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.522 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (10.438, 10.522, 10.587), stdev = 0.076
  CI (99.9%): [9.135, 11.910] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.005 ms/op
Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
Iteration   3: 2.599 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (2.531, 2.560, 2.599), stdev = 0.035
  CI (99.9%): [1.922, 3.199] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.477, 2.486, 2.496), stdev = 0.009
  CI (99.9%): [2.313, 2.658] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
Iteration   3: 2.521 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.521, 2.531, 2.542), stdev = 0.010
  CI (99.9%): [2.340, 2.722] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.750 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.005 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
Iteration   3: 3.047 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.030, 3.042, 3.050), stdev = 0.011
  CI (99.9%): [2.850, 3.234] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.754 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.614 ±(99.9%) 0.006 ms/op
Iteration   1: 2.580 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.194 ms/op
                 createUser·p0.9999: 14.890 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 12.861 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.591 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 11.441 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370945
  mean =      2.585 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 177489 
    [ 2.500,  3.750) = 188837 
    [ 3.750,  5.000) = 3629 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.302 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 13.715 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  9.231 ms/op
                 existUser·p0.9999: 12.260 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384383
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 188586 
    [ 2.500,  3.750) = 192401 
    [ 3.750,  5.000) = 2523 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.382 ms/op
     p(99.9900) =     13.970 ms/op
     p(99.9990) =     19.666 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.547 ms/op
                 getUser·p0.999:  11.229 ms/op
                 getUser·p0.9999: 14.095 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  8.629 ms/op
                 getUser·p0.9999: 13.660 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.517 ms/op
                 getUser·p0.9999: 14.574 ms/op
                 getUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377931
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 185147 
    [ 2.500,  3.750) = 188279 
    [ 3.750,  5.000) = 3506 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.193 ms/op
     p(99.9900) =     14.015 ms/op
     p(99.9990) =     14.675 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
Iteration   1: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.640 ms/op
                 listUser·p0.9999: 10.937 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   2: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.371 ms/op
                 listUser·p0.9999: 10.625 ms/op
                 listUser·p1.00:   11.076 ms/op

Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 12.026 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314273
  mean =      3.052 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 85008 
    [ 2.500,  3.750) = 188331 
    [ 3.750,  5.000) = 32985 
    [ 5.000,  6.250) = 6429 
    [ 6.250,  7.500) = 740 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 314 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.527 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.505 ± 1.117  ops/ms
ClientPb.existUser                       thrpt       3  12.981 ± 0.967  ops/ms
ClientPb.getUser                         thrpt       3  12.705 ± 1.114  ops/ms
ClientPb.listUser                        thrpt       3  10.522 ± 1.387  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.638   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.172   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.191   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.192   ms/op
ClientPb.createUser                     sample  370945   2.585 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.689           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.255           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  384383   2.495 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.957           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.382           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.825           ms/op
ClientPb.getUser                        sample  377931   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.193           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.015           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.828           ms/op
ClientPb.listUser                       sample  314273   3.052 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.861           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
