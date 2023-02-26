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
# Warmup Iteration   1: 1.899 ops/ms
# Warmup Iteration   2: 5.117 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 8.578 ops/ms
Iteration   2: 9.058 ops/ms
Iteration   3: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.918 ±(99.9%) 5.405 ops/ms [Average]
  (min, avg, max) = (8.578, 8.918, 9.119), stdev = 0.296
  CI (99.9%): [3.513, 14.323] (assumes normal distribution)


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
# Warmup Iteration   1: 2.361 ops/ms
# Warmup Iteration   2: 8.073 ops/ms
# Warmup Iteration   3: 8.991 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 8.714 ops/ms
Iteration   3: 9.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.138 ±(99.9%) 6.735 ops/ms [Average]
  (min, avg, max) = (8.714, 9.138, 9.387), stdev = 0.369
  CI (99.9%): [2.403, 15.873] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.769 ops/ms
# Warmup Iteration   2: 7.612 ops/ms
# Warmup Iteration   3: 8.579 ops/ms
Iteration   1: 8.674 ops/ms
Iteration   2: 8.714 ops/ms
Iteration   3: 8.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.632 ±(99.9%) 2.003 ops/ms [Average]
  (min, avg, max) = (8.507, 8.632, 8.714), stdev = 0.110
  CI (99.9%): [6.629, 10.634] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.255 ops/ms
# Warmup Iteration   2: 6.365 ops/ms
# Warmup Iteration   3: 7.454 ops/ms
Iteration   1: 7.439 ops/ms
Iteration   2: 7.532 ops/ms
Iteration   3: 8.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.695 ±(99.9%) 6.689 ops/ms [Average]
  (min, avg, max) = (7.439, 7.695, 8.115), stdev = 0.367
  CI (99.9%): [1.007, 14.384] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.396 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.008 ms/op
Iteration   1: 3.464 ±(99.9%) 0.009 ms/op
Iteration   2: 3.517 ±(99.9%) 0.010 ms/op
Iteration   3: 3.643 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.541 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (3.464, 3.541, 3.643), stdev = 0.092
  CI (99.9%): [1.861, 5.221] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.957 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.005 ms/op
Iteration   1: 3.461 ±(99.9%) 0.008 ms/op
Iteration   2: 3.452 ±(99.9%) 0.005 ms/op
Iteration   3: 3.471 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.461 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.452, 3.461, 3.471), stdev = 0.010
  CI (99.9%): [3.285, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 9.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.008 ms/op
Iteration   1: 3.626 ±(99.9%) 0.005 ms/op
Iteration   2: 3.573 ±(99.9%) 0.009 ms/op
Iteration   3: 3.562 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.587 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.562, 3.587, 3.626), stdev = 0.034
  CI (99.9%): [2.964, 4.210] (assumes normal distribution)


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
# Warmup Iteration   1: 12.107 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.789 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.267 ±(99.9%) 0.006 ms/op
Iteration   1: 4.221 ±(99.9%) 0.009 ms/op
Iteration   2: 4.032 ±(99.9%) 0.015 ms/op
Iteration   3: 4.157 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.136 ±(99.9%) 1.758 ms/op [Average]
  (min, avg, max) = (4.032, 4.136, 4.221), stdev = 0.096
  CI (99.9%): [2.379, 5.894] (assumes normal distribution)


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
# Warmup Iteration   1: 9.904 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.013 ms/op
Iteration   1: 3.616 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  21.908 ms/op
                 createUser·p0.9999: 26.225 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   2: 3.605 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  23.438 ms/op
                 createUser·p0.9999: 27.448 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 3.566 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  25.076 ms/op
                 createUser·p0.9999: 34.932 ms/op
                 createUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266886
  mean =      3.595 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2052 
    [ 2.500,  5.000) = 257294 
    [ 5.000,  7.500) = 5985 
    [ 7.500, 10.000) = 1032 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     36.001 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 11.581 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.011 ms/op
Iteration   1: 3.532 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.513 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  21.070 ms/op
                 existUser·p0.9999: 23.787 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  14.574 ms/op
                 existUser·p0.9999: 31.658 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  24.231 ms/op
                 existUser·p0.9999: 27.201 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274510
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4949 
    [ 2.500,  5.000) = 262710 
    [ 5.000,  7.500) = 5551 
    [ 7.500, 10.000) = 868 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     14.958 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     32.280 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 13.822 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.011 ms/op
Iteration   1: 3.774 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  17.826 ms/op
                 getUser·p0.9999: 21.742 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 4.177 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   11.862 ms/op
                 getUser·p0.999:  20.004 ms/op
                 getUser·p0.9999: 30.944 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   3: 3.556 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  23.628 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 251264
  mean =      3.819 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2630 
    [ 2.500,  5.000) = 232743 
    [ 5.000,  7.500) = 9727 
    [ 7.500, 10.000) = 3690 
    [10.000, 12.500) = 1547 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     26.374 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 10.908 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  19.495 ms/op
                 listUser·p0.9999: 24.372 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   2: 3.985 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  14.689 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.962 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 16.395 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241985
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 234231 
    [ 5.000,  7.500) = 5219 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     23.580 ms/op
     p(99.9990) =     24.947 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.918 ± 5.405  ops/ms
ClientPb.existUser                       thrpt       3   9.138 ± 6.735  ops/ms
ClientPb.getUser                         thrpt       3   8.632 ± 2.003  ops/ms
ClientPb.listUser                        thrpt       3   7.695 ± 6.689  ops/ms
ClientPb.createUser                       avgt       3   3.541 ± 1.680   ms/op
ClientPb.existUser                        avgt       3   3.461 ± 0.177   ms/op
ClientPb.getUser                          avgt       3   3.587 ± 0.623   ms/op
ClientPb.listUser                         avgt       3   4.136 ± 1.758   ms/op
ClientPb.createUser                     sample  266886   3.595 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.544           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  274510   3.497 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.513           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.958           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.605           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  251264   3.819 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.374           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178           ms/op
ClientPb.listUser                       sample  241985   3.964 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.580           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.494           ms/op
