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
# Warmup Iteration   1: 2.819 ops/ms
# Warmup Iteration   2: 6.346 ops/ms
# Warmup Iteration   3: 9.190 ops/ms
Iteration   1: 9.874 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.989 ±(99.9%) 2.092 ops/ms [Average]
  (min, avg, max) = (9.874, 9.989, 10.103), stdev = 0.115
  CI (99.9%): [7.897, 12.081] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 9.009 ops/ms
# Warmup Iteration   3: 9.797 ops/ms
Iteration   1: 10.071 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.383 ±(99.9%) 5.002 ops/ms [Average]
  (min, avg, max) = (10.071, 10.383, 10.581), stdev = 0.274
  CI (99.9%): [5.382, 15.385] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.451 ops/ms
# Warmup Iteration   2: 8.747 ops/ms
# Warmup Iteration   3: 9.631 ops/ms
Iteration   1: 10.140 ops/ms
Iteration   2: 9.627 ops/ms
Iteration   3: 10.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.942 ±(99.9%) 5.030 ops/ms [Average]
  (min, avg, max) = (9.627, 9.942, 10.140), stdev = 0.276
  CI (99.9%): [4.912, 14.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ops/ms
# Warmup Iteration   2: 7.837 ops/ms
# Warmup Iteration   3: 8.481 ops/ms
Iteration   1: 8.608 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.539 ±(99.9%) 1.207 ops/ms [Average]
  (min, avg, max) = (8.477, 8.539, 8.608), stdev = 0.066
  CI (99.9%): [7.332, 9.746] (assumes normal distribution)


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
# Warmup Iteration   1: 7.743 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.004 ms/op
Iteration   1: 3.322 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.010 ms/op
Iteration   3: 3.109 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 2.423 ms/op [Average]
  (min, avg, max) = (3.079, 3.170, 3.322), stdev = 0.133
  CI (99.9%): [0.747, 5.593] (assumes normal distribution)


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
# Warmup Iteration   1: 7.372 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.005 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
Iteration   3: 3.191 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.142 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.089, 3.142, 3.191), stdev = 0.051
  CI (99.9%): [2.204, 4.080] (assumes normal distribution)


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
# Warmup Iteration   1: 7.486 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.006 ms/op
Iteration   1: 3.111 ±(99.9%) 0.003 ms/op
Iteration   2: 3.271 ±(99.9%) 0.005 ms/op
Iteration   3: 3.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.186 ±(99.9%) 1.473 ms/op [Average]
  (min, avg, max) = (3.111, 3.186, 3.271), stdev = 0.081
  CI (99.9%): [1.713, 4.659] (assumes normal distribution)


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
# Warmup Iteration   1: 9.378 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.006 ms/op
Iteration   1: 3.721 ±(99.9%) 0.007 ms/op
Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
Iteration   3: 3.804 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.759 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.721, 3.759, 3.804), stdev = 0.042
  CI (99.9%): [2.988, 4.529] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.482 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  18.672 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.371 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 24.150 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  14.893 ms/op
                 createUser·p0.9999: 26.647 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307005
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18811 
    [ 2.500,  5.000) = 284791 
    [ 5.000,  7.500) = 2620 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.684 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  10.329 ms/op
                 existUser·p0.9999: 22.883 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  10.944 ms/op
                 existUser·p0.9999: 22.006 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 22.210 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297525
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14172 
    [ 2.500,  5.000) = 277485 
    [ 5.000,  7.500) = 5137 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     23.431 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 8.061 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.011 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  19.077 ms/op
                 getUser·p0.9999: 23.170 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.856 ms/op
                 getUser·p0.9999: 21.610 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  12.306 ms/op
                 getUser·p0.9999: 25.599 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294507
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16538 
    [ 2.500,  5.000) = 270039 
    [ 5.000,  7.500) = 7069 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 175 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     18.661 ms/op
     p(99.9900) =     24.972 ms/op
     p(99.9990) =     25.827 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 8.523 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  13.336 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  13.362 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.753 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 19.758 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254672
  mean =      3.769 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 246494 
    [ 5.000,  7.500) = 6058 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     20.432 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.989 ± 2.092  ops/ms
ClientPb.existUser                       thrpt       3  10.383 ± 5.002  ops/ms
ClientPb.getUser                         thrpt       3   9.942 ± 5.030  ops/ms
ClientPb.listUser                        thrpt       3   8.539 ± 1.207  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 2.423   ms/op
ClientPb.existUser                        avgt       3   3.142 ± 0.938   ms/op
ClientPb.getUser                          avgt       3   3.186 ± 1.473   ms/op
ClientPb.listUser                         avgt       3   3.759 ± 0.771   ms/op
ClientPb.createUser                     sample  307005   3.124 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.024           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.237           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.985           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.197           ms/op
ClientPb.existUser                      sample  297525   3.224 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.774           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.698           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.249           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.379           ms/op
ClientPb.getUser                        sample  294507   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.528           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.661           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.972           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.083           ms/op
ClientPb.listUser                       sample  254672   3.769 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.353           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.432           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.299           ms/op
