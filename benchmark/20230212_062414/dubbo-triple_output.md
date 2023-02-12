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
# Warmup Iteration   1: 1.989 ops/ms
# Warmup Iteration   2: 5.312 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 8.956 ops/ms
Iteration   2: 9.302 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.212 ±(99.9%) 4.119 ops/ms [Average]
  (min, avg, max) = (8.956, 9.212, 9.380), stdev = 0.226
  CI (99.9%): [5.094, 13.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.960 ops/ms
# Warmup Iteration   2: 9.045 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.903 ops/ms
Iteration   2: 9.109 ops/ms
Iteration   3: 9.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.500 ±(99.9%) 7.241 ops/ms [Average]
  (min, avg, max) = (9.109, 9.500, 9.903), stdev = 0.397
  CI (99.9%): [2.259, 16.741] (assumes normal distribution)


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
# Warmup Iteration   1: 2.782 ops/ms
# Warmup Iteration   2: 8.265 ops/ms
# Warmup Iteration   3: 9.403 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 9.371 ops/ms
Iteration   3: 9.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.387 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (9.287, 9.387, 9.503), stdev = 0.109
  CI (99.9%): [7.398, 11.376] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.485 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 8.022 ops/ms
Iteration   1: 7.888 ops/ms
Iteration   2: 8.161 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.058 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (7.888, 8.058, 8.161), stdev = 0.148
  CI (99.9%): [5.354, 10.762] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.006 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.007 ms/op
Iteration   2: 3.516 ±(99.9%) 0.005 ms/op
Iteration   3: 3.339 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 1.645 ms/op [Average]
  (min, avg, max) = (3.339, 3.437, 3.516), stdev = 0.090
  CI (99.9%): [1.792, 5.082] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.006 ms/op
Iteration   1: 3.278 ±(99.9%) 0.006 ms/op
Iteration   2: 3.225 ±(99.9%) 0.014 ms/op
Iteration   3: 3.347 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (3.225, 3.283, 3.347), stdev = 0.061
  CI (99.9%): [2.168, 4.399] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.511 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.004 ms/op
Iteration   1: 3.306 ±(99.9%) 0.005 ms/op
Iteration   2: 3.488 ±(99.9%) 0.005 ms/op
Iteration   3: 3.580 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.458 ±(99.9%) 2.545 ms/op [Average]
  (min, avg, max) = (3.306, 3.458, 3.580), stdev = 0.139
  CI (99.9%): [0.913, 6.003] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.755 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.854 ±(99.9%) 0.011 ms/op
Iteration   2: 3.897 ±(99.9%) 0.016 ms/op
Iteration   3: 3.992 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.914 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (3.854, 3.914, 3.992), stdev = 0.071
  CI (99.9%): [2.624, 5.204] (assumes normal distribution)


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
# Warmup Iteration   1: 10.073 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.472 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  20.050 ms/op
                 createUser·p0.9999: 28.392 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   2: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  21.094 ms/op
                 createUser·p0.9999: 24.839 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.401 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.658 ms/op
                 createUser·p0.9999: 32.984 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278624
  mean =      3.443 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3221 
    [ 2.500,  5.000) = 269542 
    [ 5.000,  7.500) = 4843 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     19.968 ms/op
     p(99.9900) =     27.908 ms/op
     p(99.9990) =     33.405 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 8.359 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
Iteration   1: 3.489 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.124 ms/op
                 existUser·p0.999:  20.295 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.724 ms/op
                 existUser·p0.999:  10.928 ms/op
                 existUser·p0.9999: 24.683 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.514 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  14.729 ms/op
                 existUser·p0.9999: 28.729 ms/op
                 existUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280265
  mean =      3.422 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12916 
    [ 2.500,  5.000) = 261105 
    [ 5.000,  7.500) = 5426 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     26.967 ms/op
     p(99.9990) =     29.203 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 9.953 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.011 ms/op
Iteration   1: 3.431 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  20.211 ms/op
                 getUser·p0.9999: 22.730 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.478 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  21.594 ms/op
                 getUser·p0.9999: 25.120 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.433 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  20.147 ms/op
                 getUser·p0.9999: 27.078 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278360
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6839 
    [ 2.500,  5.000) = 265195 
    [ 5.000,  7.500) = 5103 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     26.056 ms/op
     p(99.9990) =     27.408 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 11.025 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.014 ms/op
Iteration   1: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.052 ms/op
                 listUser·p0.999:  18.484 ms/op
                 listUser·p0.9999: 27.519 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   2: 4.046 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.918 ms/op
                 listUser·p0.999:  15.009 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.982 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241184
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 233517 
    [ 5.000,  7.500) = 5445 
    [ 7.500, 10.000) = 1443 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     25.916 ms/op
     p(99.9990) =     27.643 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.212 ± 4.119  ops/ms
ClientPb.existUser                       thrpt       3   9.500 ± 7.241  ops/ms
ClientPb.getUser                         thrpt       3   9.387 ± 1.989  ops/ms
ClientPb.listUser                        thrpt       3   8.058 ± 2.704  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 1.645   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 1.116   ms/op
ClientPb.getUser                          avgt       3   3.458 ± 2.545   ms/op
ClientPb.listUser                         avgt       3   3.914 ± 1.290   ms/op
ClientPb.createUser                     sample  278624   3.443 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.968           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.908           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  280265   3.422 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.473           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.729           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.967           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.557           ms/op
ClientPb.getUser                        sample  278360   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.056           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  241184   3.977 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.916           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.951           ms/op
