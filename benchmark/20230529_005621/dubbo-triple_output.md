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
# Warmup Iteration   1: 1.731 ops/ms
# Warmup Iteration   2: 3.783 ops/ms
# Warmup Iteration   3: 7.148 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 8.317 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.147 ±(99.9%) 6.876 ops/ms [Average]
  (min, avg, max) = (7.715, 8.147, 8.408), stdev = 0.377
  CI (99.9%): [1.271, 15.023] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.812 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.250 ops/ms
Iteration   2: 8.796 ops/ms
Iteration   3: 8.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.591 ±(99.9%) 5.426 ops/ms [Average]
  (min, avg, max) = (8.250, 8.591, 8.796), stdev = 0.297
  CI (99.9%): [3.166, 14.017] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.384 ops/ms
# Warmup Iteration   2: 6.528 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 8.429 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.116 ±(99.9%) 4.940 ops/ms [Average]
  (min, avg, max) = (7.957, 8.116, 8.429), stdev = 0.271
  CI (99.9%): [3.177, 13.056] (assumes normal distribution)


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
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 5.547 ops/ms
# Warmup Iteration   3: 6.914 ops/ms
Iteration   1: 6.927 ops/ms
Iteration   2: 6.868 ops/ms
Iteration   3: 6.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.927 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (6.868, 6.927, 6.987), stdev = 0.059
  CI (99.9%): [5.843, 8.012] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.188 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.943 ±(99.9%) 0.010 ms/op
Iteration   2: 3.982 ±(99.9%) 0.006 ms/op
Iteration   3: 3.833 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.919 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.833, 3.919, 3.982), stdev = 0.078
  CI (99.9%): [2.504, 5.335] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.218 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.003 ms/op
Iteration   1: 3.861 ±(99.9%) 0.009 ms/op
Iteration   2: 3.721 ±(99.9%) 0.013 ms/op
Iteration   3: 3.762 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.781 ±(99.9%) 1.311 ms/op [Average]
  (min, avg, max) = (3.721, 3.781, 3.861), stdev = 0.072
  CI (99.9%): [2.471, 5.092] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.248 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
Iteration   2: 3.819 ±(99.9%) 0.010 ms/op
Iteration   3: 3.782 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.798 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (3.782, 3.798, 3.819), stdev = 0.019
  CI (99.9%): [3.453, 4.143] (assumes normal distribution)


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
# Warmup Iteration   1: 13.898 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.229 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.011 ms/op
Iteration   1: 4.546 ±(99.9%) 0.009 ms/op
Iteration   2: 4.475 ±(99.9%) 0.016 ms/op
Iteration   3: 4.715 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.579 ±(99.9%) 2.255 ms/op [Average]
  (min, avg, max) = (4.475, 4.579, 4.715), stdev = 0.124
  CI (99.9%): [2.323, 6.834] (assumes normal distribution)


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
# Warmup Iteration   1: 11.271 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 5.099 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.018 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.931 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  14.125 ms/op
                 createUser·p0.9999: 26.478 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.914 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  24.975 ms/op
                 createUser·p0.9999: 27.060 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.865 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   7.297 ms/op
                 createUser·p0.999:  27.492 ms/op
                 createUser·p0.9999: 31.055 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243402
  mean =      3.944 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 405 
    [ 2.500,  5.000) = 226420 
    [ 5.000,  7.500) = 14332 
    [ 7.500, 10.000) = 1541 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     23.390 ms/op
     p(99.9900) =     30.692 ms/op
     p(99.9990) =     31.405 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 11.048 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   7.325 ms/op
                 existUser·p0.999:  21.823 ms/op
                 existUser·p0.9999: 30.439 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  12.379 ms/op
                 existUser·p0.9999: 27.668 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   3: 3.657 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  25.494 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255416
  mean =      3.758 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 447 
    [ 2.500,  5.000) = 246505 
    [ 5.000,  7.500) = 6981 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     21.002 ms/op
     p(99.9900) =     29.226 ms/op
     p(99.9990) =     31.006 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.903 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.295 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
Iteration   1: 4.060 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.847 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 26.533 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.378 ms/op
                 getUser·p0.999:  24.791 ms/op
                 getUser·p0.9999: 26.856 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.782 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  10.322 ms/op
                 getUser·p0.9999: 30.872 ms/op
                 getUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244834
  mean =      3.921 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 234380 
    [ 5.000,  7.500) = 7768 
    [ 7.500, 10.000) = 1980 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     19.470 ms/op
     p(99.9900) =     30.180 ms/op
     p(99.9990) =     31.318 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 14.079 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.167 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.584 ±(99.9%) 0.016 ms/op
Iteration   1: 4.692 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  25.157 ms/op
                 listUser·p0.9999: 27.124 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   2: 4.643 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.761 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 21.835 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 4.653 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205695
  mean =      4.663 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 173568 
    [ 5.000,  7.500) = 27545 
    [ 7.500, 10.000) = 3489 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     19.114 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     27.825 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.147 ± 6.876  ops/ms
ClientPb.existUser                       thrpt       3   8.591 ± 5.426  ops/ms
ClientPb.getUser                         thrpt       3   8.116 ± 4.940  ops/ms
ClientPb.listUser                        thrpt       3   6.927 ± 1.084  ops/ms
ClientPb.createUser                       avgt       3   3.919 ± 1.416   ms/op
ClientPb.existUser                        avgt       3   3.781 ± 1.311   ms/op
ClientPb.getUser                          avgt       3   3.798 ± 0.345   ms/op
ClientPb.listUser                         avgt       3   4.579 ± 2.255   ms/op
ClientPb.createUser                     sample  243402   3.944 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.348           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.390           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.735           ms/op
ClientPb.existUser                      sample  255416   3.758 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.002           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.226           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.261           ms/op
ClientPb.getUser                        sample  244834   3.921 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.491           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.470           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.180           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.080           ms/op
ClientPb.listUser                       sample  205695   4.663 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.114           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.640           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
