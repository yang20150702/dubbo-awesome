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
# Warmup Iteration   1: 2.329 ops/ms
# Warmup Iteration   2: 6.010 ops/ms
# Warmup Iteration   3: 9.191 ops/ms
Iteration   1: 9.795 ops/ms
Iteration   2: 9.584 ops/ms
Iteration   3: 9.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.600 ±(99.9%) 3.416 ops/ms [Average]
  (min, avg, max) = (9.422, 9.600, 9.795), stdev = 0.187
  CI (99.9%): [6.184, 13.017] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.224 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 9.466 ops/ms
Iteration   1: 9.994 ops/ms
Iteration   2: 10.135 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.158 ±(99.9%) 3.229 ops/ms [Average]
  (min, avg, max) = (9.994, 10.158, 10.346), stdev = 0.177
  CI (99.9%): [6.929, 13.387] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 8.772 ops/ms
# Warmup Iteration   3: 9.206 ops/ms
Iteration   1: 9.952 ops/ms
Iteration   2: 9.617 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.787 ±(99.9%) 3.051 ops/ms [Average]
  (min, avg, max) = (9.617, 9.787, 9.952), stdev = 0.167
  CI (99.9%): [6.737, 12.838] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.116 ops/ms
# Warmup Iteration   2: 7.273 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.477 ops/ms
Iteration   2: 8.399 ops/ms
Iteration   3: 8.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.484 ±(99.9%) 1.632 ops/ms [Average]
  (min, avg, max) = (8.399, 8.484, 8.577), stdev = 0.089
  CI (99.9%): [6.852, 10.117] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.300 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.003 ms/op
Iteration   1: 3.253 ±(99.9%) 0.009 ms/op
Iteration   2: 3.180 ±(99.9%) 0.009 ms/op
Iteration   3: 3.206 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.213 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.180, 3.213, 3.253), stdev = 0.037
  CI (99.9%): [2.542, 3.884] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.220 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.005 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
Iteration   3: 3.077 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.077, 3.112, 3.139), stdev = 0.032
  CI (99.9%): [2.530, 3.693] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.511 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.005 ms/op
Iteration   1: 3.305 ±(99.9%) 0.004 ms/op
Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
Iteration   3: 3.245 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.232 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.146, 3.232, 3.305), stdev = 0.080
  CI (99.9%): [1.772, 4.693] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.400 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.786 ±(99.9%) 0.008 ms/op
Iteration   2: 3.794 ±(99.9%) 0.008 ms/op
Iteration   3: 3.945 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.842 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (3.786, 3.842, 3.945), stdev = 0.090
  CI (99.9%): [2.203, 5.480] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.495 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.610 ms/op
                 createUser·p0.999:  17.294 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  20.517 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  16.064 ms/op
                 createUser·p0.9999: 21.504 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292144
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19915 
    [ 2.500,  5.000) = 266330 
    [ 5.000,  7.500) = 4690 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 180 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     17.095 ms/op
     p(99.9900) =     21.678 ms/op
     p(99.9990) =     22.865 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 8.331 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 18.842 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  12.523 ms/op
                 existUser·p0.9999: 23.984 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 20.042 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305620
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25553 
    [ 2.500,  5.000) = 275329 
    [ 5.000,  7.500) = 3893 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.327 ms/op
     p(99.9900) =     22.835 ms/op
     p(99.9990) =     24.634 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.789 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.012 ms/op
Iteration   1: 3.243 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  16.072 ms/op
                 getUser·p0.9999: 23.474 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  19.798 ms/op
                 getUser·p0.9999: 22.913 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.378 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292172
  mean =      3.286 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14385 
    [ 2.500,  5.000) = 271120 
    [ 5.000,  7.500) = 5688 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     15.985 ms/op
     p(99.9900) =     24.045 ms/op
     p(99.9990) =     25.857 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.776 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.014 ms/op
Iteration   1: 3.889 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 22.766 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   3: 3.739 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251569
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 243379 
    [ 5.000,  7.500) = 5984 
    [ 7.500, 10.000) = 1317 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 180 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.600 ± 3.416  ops/ms
ClientPb.existUser                       thrpt       3  10.158 ± 3.229  ops/ms
ClientPb.getUser                         thrpt       3   9.787 ± 3.051  ops/ms
ClientPb.listUser                        thrpt       3   8.484 ± 1.632  ops/ms
ClientPb.createUser                       avgt       3   3.213 ± 0.671   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 0.582   ms/op
ClientPb.getUser                          avgt       3   3.232 ± 1.461   ms/op
ClientPb.listUser                         avgt       3   3.842 ± 1.638   ms/op
ClientPb.createUser                     sample  292144   3.285 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.081           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.095           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.678           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.347           ms/op
ClientPb.existUser                      sample  305620   3.141 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.983           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.327           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.835           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.740           ms/op
ClientPb.getUser                        sample  292172   3.286 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.977           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.985           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.045           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.542           ms/op
ClientPb.listUser                       sample  251569   3.817 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.596           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.216           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
