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
# Warmup Iteration   1: 2.321 ops/ms
# Warmup Iteration   2: 6.036 ops/ms
# Warmup Iteration   3: 8.457 ops/ms
Iteration   1: 8.420 ops/ms
Iteration   2: 9.141 ops/ms
Iteration   3: 9.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.941 ±(99.9%) 8.299 ops/ms [Average]
  (min, avg, max) = (8.420, 8.941, 9.262), stdev = 0.455
  CI (99.9%): [0.642, 17.239] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.528 ops/ms
# Warmup Iteration   2: 8.566 ops/ms
# Warmup Iteration   3: 9.587 ops/ms
Iteration   1: 9.572 ops/ms
Iteration   2: 9.577 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.566 ±(99.9%) 0.276 ops/ms [Average]
  (min, avg, max) = (9.548, 9.566, 9.577), stdev = 0.015
  CI (99.9%): [9.290, 9.841] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 8.568 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.546 ops/ms
Iteration   2: 9.578 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.504 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (9.390, 9.504, 9.578), stdev = 0.100
  CI (99.9%): [7.673, 11.335] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.834 ops/ms
# Warmup Iteration   2: 7.092 ops/ms
# Warmup Iteration   3: 7.682 ops/ms
Iteration   1: 8.202 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 7.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.062 ±(99.9%) 3.435 ops/ms [Average]
  (min, avg, max) = (7.848, 8.062, 8.202), stdev = 0.188
  CI (99.9%): [4.627, 11.498] (assumes normal distribution)


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
# Warmup Iteration   1: 8.834 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.008 ms/op
Iteration   1: 3.434 ±(99.9%) 0.011 ms/op
Iteration   2: 3.517 ±(99.9%) 0.003 ms/op
Iteration   3: 3.465 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.472 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.434, 3.472, 3.517), stdev = 0.042
  CI (99.9%): [2.708, 4.236] (assumes normal distribution)


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
# Warmup Iteration   1: 9.640 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.004 ms/op
Iteration   1: 3.326 ±(99.9%) 0.004 ms/op
Iteration   2: 3.504 ±(99.9%) 0.004 ms/op
Iteration   3: 3.368 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.399 ±(99.9%) 1.701 ms/op [Average]
  (min, avg, max) = (3.326, 3.399, 3.504), stdev = 0.093
  CI (99.9%): [1.698, 5.100] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.714 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.002 ms/op
Iteration   1: 3.564 ±(99.9%) 0.008 ms/op
Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
Iteration   3: 3.387 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.469 ±(99.9%) 1.630 ms/op [Average]
  (min, avg, max) = (3.387, 3.469, 3.564), stdev = 0.089
  CI (99.9%): [1.839, 5.098] (assumes normal distribution)


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
# Warmup Iteration   1: 10.659 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.009 ms/op
Iteration   1: 4.259 ±(99.9%) 0.009 ms/op
Iteration   2: 3.882 ±(99.9%) 0.015 ms/op
Iteration   3: 3.933 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.025 ±(99.9%) 3.731 ms/op [Average]
  (min, avg, max) = (3.882, 4.025, 4.259), stdev = 0.205
  CI (99.9%): [0.293, 7.756] (assumes normal distribution)


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
# Warmup Iteration   1: 9.104 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.010 ms/op
Iteration   1: 3.555 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  20.285 ms/op
                 createUser·p0.9999: 22.316 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 3.589 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  9.436 ms/op
                 createUser·p0.9999: 25.497 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  19.679 ms/op
                 createUser·p0.9999: 27.914 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270214
  mean =      3.550 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4237 
    [ 2.500,  5.000) = 258976 
    [ 5.000,  7.500) = 6036 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     28.220 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.112 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.008 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.793 ms/op
                 existUser·p0.9999: 22.652 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.352 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  20.423 ms/op
                 existUser·p0.9999: 23.790 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  13.521 ms/op
                 existUser·p0.9999: 26.226 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289094
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11712 
    [ 2.500,  5.000) = 272036 
    [ 5.000,  7.500) = 4597 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.118 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.745 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 9.428 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.010 ms/op
Iteration   1: 3.453 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  19.506 ms/op
                 getUser·p0.9999: 22.899 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.443 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  18.458 ms/op
                 getUser·p0.9999: 27.623 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278197
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2394 
    [ 2.500,  5.000) = 268313 
    [ 5.000,  7.500) = 6517 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     25.931 ms/op
     p(99.9990) =     28.450 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 11.004 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.014 ms/op
Iteration   1: 3.991 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  20.807 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 3.993 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   16.368 ms/op

Iteration   3: 4.161 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.020 ms/op
                 listUser·p0.9999: 19.943 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236982
  mean =      4.047 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 229021 
    [ 5.000,  7.500) = 6247 
    [ 7.500, 10.000) = 964 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.829 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.847 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.941 ± 8.299  ops/ms
ClientPb.existUser                       thrpt       3   9.566 ± 0.276  ops/ms
ClientPb.getUser                         thrpt       3   9.504 ± 1.831  ops/ms
ClientPb.listUser                        thrpt       3   8.062 ± 3.435  ops/ms
ClientPb.createUser                       avgt       3   3.472 ± 0.764   ms/op
ClientPb.existUser                        avgt       3   3.399 ± 1.701   ms/op
ClientPb.getUser                          avgt       3   3.469 ± 1.630   ms/op
ClientPb.listUser                         avgt       3   4.025 ± 3.731   ms/op
ClientPb.createUser                     sample  270214   3.550 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.563           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.263           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  289094   3.317 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.194           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.118           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.296           ms/op
ClientPb.getUser                        sample  278197   3.449 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.764           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.931           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  236982   4.047 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.936           ms/op
