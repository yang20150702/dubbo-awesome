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
# Warmup Iteration   1: 2.087 ops/ms
# Warmup Iteration   2: 5.379 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 9.063 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.238 ±(99.9%) 3.311 ops/ms [Average]
  (min, avg, max) = (9.063, 9.238, 9.426), stdev = 0.181
  CI (99.9%): [5.927, 12.549] (assumes normal distribution)


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
# Warmup Iteration   1: 2.933 ops/ms
# Warmup Iteration   2: 8.775 ops/ms
# Warmup Iteration   3: 9.107 ops/ms
Iteration   1: 9.532 ops/ms
Iteration   2: 9.581 ops/ms
Iteration   3: 9.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.585 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (9.532, 9.585, 9.643), stdev = 0.056
  CI (99.9%): [8.566, 10.605] (assumes normal distribution)


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
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 8.375 ops/ms
# Warmup Iteration   3: 9.177 ops/ms
Iteration   1: 9.189 ops/ms
Iteration   2: 9.538 ops/ms
Iteration   3: 9.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.289 ±(99.9%) 3.969 ops/ms [Average]
  (min, avg, max) = (9.139, 9.289, 9.538), stdev = 0.218
  CI (99.9%): [5.320, 13.257] (assumes normal distribution)


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
# Warmup Iteration   1: 2.656 ops/ms
# Warmup Iteration   2: 7.442 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 7.892 ops/ms
Iteration   2: 8.052 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.972 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (7.892, 7.972, 8.052), stdev = 0.080
  CI (99.9%): [6.520, 9.424] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.012 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.630 ±(99.9%) 0.002 ms/op
Iteration   1: 3.503 ±(99.9%) 0.004 ms/op
Iteration   2: 3.391 ±(99.9%) 0.007 ms/op
Iteration   3: 3.467 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.454 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.391, 3.454, 3.503), stdev = 0.057
  CI (99.9%): [2.415, 4.492] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.238 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.004 ms/op
Iteration   1: 3.305 ±(99.9%) 0.005 ms/op
Iteration   2: 3.424 ±(99.9%) 0.004 ms/op
Iteration   3: 3.281 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.337 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.281, 3.337, 3.424), stdev = 0.076
  CI (99.9%): [1.942, 4.731] (assumes normal distribution)


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
# Warmup Iteration   1: 10.297 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.002 ms/op
Iteration   1: 3.548 ±(99.9%) 0.003 ms/op
Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
Iteration   3: 3.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.530 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.512, 3.530, 3.548), stdev = 0.018
  CI (99.9%): [3.202, 3.857] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.661 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.006 ms/op
Iteration   1: 4.154 ±(99.9%) 0.004 ms/op
Iteration   2: 4.150 ±(99.9%) 0.006 ms/op
Iteration   3: 4.015 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.106 ±(99.9%) 1.444 ms/op [Average]
  (min, avg, max) = (4.015, 4.106, 4.154), stdev = 0.079
  CI (99.9%): [2.663, 5.550] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.530 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.009 ms/op
Iteration   1: 3.481 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.902 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 23.063 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.564 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  22.354 ms/op
                 createUser·p0.9999: 24.871 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.528 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  17.933 ms/op
                 createUser·p0.9999: 24.912 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272407
  mean =      3.524 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5167 
    [ 2.500,  5.000) = 261666 
    [ 5.000,  7.500) = 4474 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     18.388 ms/op
     p(99.9900) =     24.495 ms/op
     p(99.9990) =     25.890 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 8.250 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.009 ms/op
Iteration   1: 3.394 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  19.520 ms/op
                 existUser·p0.9999: 25.676 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  22.348 ms/op
                 existUser·p0.9999: 27.185 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   3: 3.518 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  19.661 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279048
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7023 
    [ 2.500,  5.000) = 265482 
    [ 5.000,  7.500) = 5374 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.012 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     19.692 ms/op
     p(99.9900) =     26.349 ms/op
     p(99.9990) =     27.544 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 10.551 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
Iteration   1: 3.571 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 22.489 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.563 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  21.240 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.485 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  17.800 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271264
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5383 
    [ 2.500,  5.000) = 259600 
    [ 5.000,  7.500) = 5126 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 148 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     18.505 ms/op
     p(99.9900) =     26.177 ms/op
     p(99.9990) =     27.914 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 11.217 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.013 ms/op
Iteration   1: 4.171 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  20.651 ms/op
                 listUser·p0.9999: 23.411 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.101 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.186 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231124
  mean =      4.153 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 223311 
    [ 5.000,  7.500) = 5875 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 264 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     24.369 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.238 ± 3.311  ops/ms
ClientPb.existUser                       thrpt       3   9.585 ± 1.020  ops/ms
ClientPb.getUser                         thrpt       3   9.289 ± 3.969  ops/ms
ClientPb.listUser                        thrpt       3   7.972 ± 1.452  ops/ms
ClientPb.createUser                       avgt       3   3.454 ± 1.039   ms/op
ClientPb.existUser                        avgt       3   3.337 ± 1.394   ms/op
ClientPb.getUser                          avgt       3   3.530 ± 0.328   ms/op
ClientPb.listUser                         avgt       3   4.106 ± 1.444   ms/op
ClientPb.createUser                     sample  272407   3.524 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.388           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018           ms/op
ClientPb.existUser                      sample  279048   3.440 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.012           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.931           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.692           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.349           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  271264   3.539 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.505           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.177           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  231124   4.153 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.446           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
