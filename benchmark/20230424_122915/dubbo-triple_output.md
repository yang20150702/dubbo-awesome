# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.037 ops/ms
# Warmup Iteration   2: 5.738 ops/ms
# Warmup Iteration   3: 7.114 ops/ms
Iteration   1: 8.914 ops/ms
Iteration   2: 9.326 ops/ms
Iteration   3: 9.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.108 ±(99.9%) 3.778 ops/ms [Average]
  (min, avg, max) = (8.914, 9.108, 9.326), stdev = 0.207
  CI (99.9%): [5.330, 12.886] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.972 ops/ms
# Warmup Iteration   2: 5.399 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 9.623 ops/ms
Iteration   2: 9.419 ops/ms
Iteration   3: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.491 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (9.419, 9.491, 9.623), stdev = 0.114
  CI (99.9%): [7.409, 11.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.627 ops/ms
# Warmup Iteration   2: 8.179 ops/ms
# Warmup Iteration   3: 9.023 ops/ms
Iteration   1: 9.056 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.369 ±(99.9%) 5.009 ops/ms [Average]
  (min, avg, max) = (9.056, 9.369, 9.566), stdev = 0.275
  CI (99.9%): [4.360, 14.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.741 ops/ms
# Warmup Iteration   2: 7.022 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.961 ±(99.9%) 2.939 ops/ms [Average]
  (min, avg, max) = (7.836, 7.961, 8.143), stdev = 0.161
  CI (99.9%): [5.022, 10.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.759 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.009 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
Iteration   2: 3.678 ±(99.9%) 0.011 ms/op
Iteration   3: 4.101 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.761 ±(99.9%) 5.601 ms/op [Average]
  (min, avg, max) = (3.504, 3.761, 4.101), stdev = 0.307
  CI (99.9%): [≈ 0, 9.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.240 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.896 ±(99.9%) 0.016 ms/op
Iteration   1: 3.931 ±(99.9%) 0.011 ms/op
Iteration   2: 3.364 ±(99.9%) 0.005 ms/op
Iteration   3: 3.226 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.507 ±(99.9%) 6.820 ms/op [Average]
  (min, avg, max) = (3.226, 3.507, 3.931), stdev = 0.374
  CI (99.9%): [≈ 0, 10.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.072 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.005 ms/op
Iteration   1: 3.444 ±(99.9%) 0.009 ms/op
Iteration   2: 3.356 ±(99.9%) 0.011 ms/op
Iteration   3: 3.421 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.407 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.356, 3.407, 3.444), stdev = 0.046
  CI (99.9%): [2.575, 4.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.257 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.009 ms/op
Iteration   1: 4.105 ±(99.9%) 0.008 ms/op
Iteration   2: 4.161 ±(99.9%) 0.008 ms/op
Iteration   3: 3.958 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.075 ±(99.9%) 1.908 ms/op [Average]
  (min, avg, max) = (3.958, 4.075, 4.161), stdev = 0.105
  CI (99.9%): [2.167, 5.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.532 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.015 ms/op
Iteration   1: 3.493 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.812 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  22.624 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   2: 3.503 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.507 ms/op
                 createUser·p0.999:  24.034 ms/op
                 createUser·p0.9999: 26.886 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.589 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 29.279 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271949
  mean =      3.528 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8879 
    [ 2.500,  5.000) = 254569 
    [ 5.000,  7.500) = 7181 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     21.825 ms/op
     p(99.9900) =     31.379 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.536 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
Iteration   1: 3.300 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 26.847 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  22.482 ms/op
                 existUser·p0.9999: 24.779 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  22.344 ms/op
                 existUser·p0.9999: 26.755 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286081
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16146 
    [ 2.500,  5.000) = 264080 
    [ 5.000,  7.500) = 4841 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     26.299 ms/op
     p(99.9990) =     27.628 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.716 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.013 ms/op
Iteration   1: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 26.572 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 3.488 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  21.582 ms/op
                 getUser·p0.9999: 24.112 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.460 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  9.339 ms/op
                 getUser·p0.9999: 26.862 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274865
  mean =      3.488 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1539 
    [ 2.500,  5.000) = 266354 
    [ 5.000,  7.500) = 5931 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     19.023 ms/op
     p(99.9900) =     26.379 ms/op
     p(99.9990) =     28.107 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.251 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.013 ms/op
Iteration   1: 4.147 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  21.817 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 3.973 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 18.021 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.068 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236234
  mean =      4.061 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 223926 
    [ 5.000,  7.500) = 10344 
    [ 7.500, 10.000) = 1061 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 264 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     27.284 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.108 ± 3.778  ops/ms
ClientPb.existUser                       thrpt       3   9.491 ± 2.082  ops/ms
ClientPb.getUser                         thrpt       3   9.369 ± 5.009  ops/ms
ClientPb.listUser                        thrpt       3   7.961 ± 2.939  ops/ms
ClientPb.createUser                       avgt       3   3.761 ± 5.601   ms/op
ClientPb.existUser                        avgt       3   3.507 ± 6.820   ms/op
ClientPb.getUser                          avgt       3   3.407 ± 0.831   ms/op
ClientPb.listUser                         avgt       3   4.075 ± 1.908   ms/op
ClientPb.createUser                     sample  271949   3.528 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.825           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.379           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  286081   3.355 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.882           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.272           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.299           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.689           ms/op
ClientPb.getUser                        sample  274865   3.488 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.023           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.379           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.213           ms/op
ClientPb.listUser                       sample  236234   4.061 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.710           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.728           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.510           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
