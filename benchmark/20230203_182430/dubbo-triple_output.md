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
# Warmup Iteration   1: 2.067 ops/ms
# Warmup Iteration   2: 5.099 ops/ms
# Warmup Iteration   3: 8.493 ops/ms
Iteration   1: 8.944 ops/ms
Iteration   2: 9.550 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.271 ±(99.9%) 5.575 ops/ms [Average]
  (min, avg, max) = (8.944, 9.271, 9.550), stdev = 0.306
  CI (99.9%): [3.696, 14.846] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.931 ops/ms
# Warmup Iteration   2: 8.847 ops/ms
# Warmup Iteration   3: 9.142 ops/ms
Iteration   1: 9.677 ops/ms
Iteration   2: 9.697 ops/ms
Iteration   3: 9.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.650 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (9.577, 9.650, 9.697), stdev = 0.064
  CI (99.9%): [8.476, 10.824] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.946 ops/ms
# Warmup Iteration   2: 8.388 ops/ms
# Warmup Iteration   3: 9.038 ops/ms
Iteration   1: 8.823 ops/ms
Iteration   2: 9.486 ops/ms
Iteration   3: 8.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.990 ±(99.9%) 7.958 ops/ms [Average]
  (min, avg, max) = (8.663, 8.990, 9.486), stdev = 0.436
  CI (99.9%): [1.033, 16.948] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.609 ops/ms
# Warmup Iteration   2: 7.115 ops/ms
# Warmup Iteration   3: 7.693 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 8.249 ops/ms
Iteration   3: 7.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.965 ±(99.9%) 5.627 ops/ms [Average]
  (min, avg, max) = (7.637, 7.965, 8.249), stdev = 0.308
  CI (99.9%): [2.338, 13.592] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.558 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.003 ms/op
Iteration   1: 3.529 ±(99.9%) 0.004 ms/op
Iteration   2: 3.427 ±(99.9%) 0.010 ms/op
Iteration   3: 3.396 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (3.396, 3.450, 3.529), stdev = 0.070
  CI (99.9%): [2.182, 4.719] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.215 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.006 ms/op
Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
Iteration   3: 3.219 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.300 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.219, 3.300, 3.369), stdev = 0.076
  CI (99.9%): [1.918, 4.682] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.334 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.008 ms/op
Iteration   1: 3.408 ±(99.9%) 0.005 ms/op
Iteration   2: 3.343 ±(99.9%) 0.008 ms/op
Iteration   3: 3.493 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.414 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (3.343, 3.414, 3.493), stdev = 0.075
  CI (99.9%): [2.040, 4.789] (assumes normal distribution)


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
# Warmup Iteration   1: 11.655 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.004 ms/op
Iteration   1: 3.973 ±(99.9%) 0.017 ms/op
Iteration   2: 4.082 ±(99.9%) 0.008 ms/op
Iteration   3: 4.016 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.024 ±(99.9%) 0.998 ms/op [Average]
  (min, avg, max) = (3.973, 4.024, 4.082), stdev = 0.055
  CI (99.9%): [3.026, 5.022] (assumes normal distribution)


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
# Warmup Iteration   1: 9.272 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
Iteration   1: 3.463 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.464 ms/op
                 createUser·p0.9999: 22.995 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  23.216 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  17.715 ms/op
                 createUser·p0.9999: 26.891 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280607
  mean =      3.422 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12901 
    [ 2.500,  5.000) = 261372 
    [ 5.000,  7.500) = 5337 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     17.937 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 8.817 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.008 ms/op
Iteration   1: 3.337 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  19.542 ms/op
                 existUser·p0.9999: 24.164 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.465 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  22.188 ms/op
                 existUser·p0.9999: 26.829 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 3.441 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  19.726 ms/op
                 existUser·p0.9999: 31.307 ms/op
                 existUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281161
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7680 
    [ 2.500,  5.000) = 267848 
    [ 5.000,  7.500) = 4760 
    [ 7.500, 10.000) = 494 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     19.754 ms/op
     p(99.9900) =     30.143 ms/op
     p(99.9990) =     31.791 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 9.857 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.012 ms/op
Iteration   1: 3.455 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   7.140 ms/op
                 getUser·p0.999:  21.945 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   2: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.870 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  10.174 ms/op
                 getUser·p0.9999: 31.248 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  20.404 ms/op
                 getUser·p0.9999: 28.622 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275899
  mean =      3.477 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11484 
    [ 2.500,  5.000) = 256965 
    [ 5.000,  7.500) = 6230 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     15.026 ms/op
     p(99.9900) =     30.376 ms/op
     p(99.9990) =     31.690 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 11.947 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.165 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 25.464 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.926 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.008 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241637
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 233176 
    [ 5.000,  7.500) = 6290 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 274 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     16.292 ms/op
     p(99.9900) =     23.309 ms/op
     p(99.9990) =     26.113 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.271 ± 5.575  ops/ms
ClientPb.existUser                       thrpt       3   9.650 ± 1.174  ops/ms
ClientPb.getUser                         thrpt       3   8.990 ± 7.958  ops/ms
ClientPb.listUser                        thrpt       3   7.965 ± 5.627  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 1.268   ms/op
ClientPb.existUser                        avgt       3   3.300 ± 1.382   ms/op
ClientPb.getUser                          avgt       3   3.414 ± 1.374   ms/op
ClientPb.listUser                         avgt       3   4.024 ± 0.998   ms/op
ClientPb.createUser                     sample  280607   3.422 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.159           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.937           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.739           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  281161   3.413 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.947           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.754           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.143           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  275899   3.477 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.744           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.026           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.376           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702           ms/op
ClientPb.listUser                       sample  241637   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.292           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.309           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.280           ms/op
