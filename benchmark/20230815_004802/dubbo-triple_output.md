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
# Warmup Iteration   1: 1.215 ops/ms
# Warmup Iteration   2: 2.594 ops/ms
# Warmup Iteration   3: 5.588 ops/ms
Iteration   1: 5.892 ops/ms
Iteration   2: 6.322 ops/ms
Iteration   3: 6.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.152 ±(99.9%) 4.173 ops/ms [Average]
  (min, avg, max) = (5.892, 6.152, 6.322), stdev = 0.229
  CI (99.9%): [1.979, 10.324] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.939 ops/ms
# Warmup Iteration   2: 4.997 ops/ms
# Warmup Iteration   3: 6.373 ops/ms
Iteration   1: 6.555 ops/ms
Iteration   2: 6.550 ops/ms
Iteration   3: 6.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.520 ±(99.9%) 1.008 ops/ms [Average]
  (min, avg, max) = (6.457, 6.520, 6.555), stdev = 0.055
  CI (99.9%): [5.512, 7.529] (assumes normal distribution)


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
# Warmup Iteration   1: 1.714 ops/ms
# Warmup Iteration   2: 5.358 ops/ms
# Warmup Iteration   3: 6.370 ops/ms
Iteration   1: 6.227 ops/ms
Iteration   2: 6.232 ops/ms
Iteration   3: 6.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.265 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (6.227, 6.265, 6.334), stdev = 0.060
  CI (99.9%): [5.162, 7.367] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.697 ops/ms
# Warmup Iteration   2: 4.709 ops/ms
# Warmup Iteration   3: 5.239 ops/ms
Iteration   1: 5.219 ops/ms
Iteration   2: 5.364 ops/ms
Iteration   3: 5.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.254 ±(99.9%) 1.765 ops/ms [Average]
  (min, avg, max) = (5.180, 5.254, 5.364), stdev = 0.097
  CI (99.9%): [3.490, 7.019] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.182 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.311 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.967 ±(99.9%) 0.009 ms/op
Iteration   1: 5.165 ±(99.9%) 0.012 ms/op
Iteration   2: 4.937 ±(99.9%) 0.013 ms/op
Iteration   3: 5.164 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.089 ±(99.9%) 2.399 ms/op [Average]
  (min, avg, max) = (4.937, 5.089, 5.165), stdev = 0.131
  CI (99.9%): [2.690, 7.487] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 14.775 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.229 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.008 ms/op
Iteration   1: 4.898 ±(99.9%) 0.012 ms/op
Iteration   2: 4.923 ±(99.9%) 0.010 ms/op
Iteration   3: 4.795 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.872 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (4.795, 4.872, 4.923), stdev = 0.068
  CI (99.9%): [3.638, 6.106] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.458 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.578 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.150 ±(99.9%) 0.008 ms/op
Iteration   1: 5.476 ±(99.9%) 0.009 ms/op
Iteration   2: 5.234 ±(99.9%) 0.014 ms/op
Iteration   3: 5.124 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.278 ±(99.9%) 3.283 ms/op [Average]
  (min, avg, max) = (5.124, 5.278, 5.476), stdev = 0.180
  CI (99.9%): [1.995, 8.561] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.766 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.429 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.235 ±(99.9%) 0.014 ms/op
Iteration   1: 6.342 ±(99.9%) 0.016 ms/op
Iteration   2: 5.966 ±(99.9%) 0.020 ms/op
Iteration   3: 5.930 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.079 ±(99.9%) 4.156 ms/op [Average]
  (min, avg, max) = (5.930, 6.079, 6.342), stdev = 0.228
  CI (99.9%): [1.923, 10.236] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.001 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.802 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.790 ±(99.9%) 0.029 ms/op
Iteration   1: 5.230 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.540 ms/op
                 createUser·p0.99:   9.694 ms/op
                 createUser·p0.999:  22.343 ms/op
                 createUser·p0.9999: 29.393 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   2: 5.069 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.017 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.053 ms/op
                 createUser·p0.99:   9.305 ms/op
                 createUser·p0.999:  26.050 ms/op
                 createUser·p0.9999: 31.021 ms/op
                 createUser·p1.00:   31.654 ms/op

Iteration   3: 5.270 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  29.382 ms/op
                 createUser·p0.9999: 40.825 ms/op
                 createUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184797
  mean =      5.188 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 101396 
    [ 5.000, 10.000) = 81715 
    [10.000, 15.000) = 1350 
    [15.000, 20.000) = 112 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 114 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     24.851 ms/op
     p(99.9900) =     39.783 ms/op
     p(99.9990) =     42.084 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.562 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 6.054 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.959 ±(99.9%) 0.017 ms/op
Iteration   1: 5.014 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   6.857 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  24.299 ms/op
                 existUser·p0.9999: 30.974 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   2: 5.017 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.479 ms/op
                 existUser·p0.99:   10.068 ms/op
                 existUser·p0.999:  24.838 ms/op
                 existUser·p0.9999: 29.983 ms/op
                 existUser·p1.00:   31.687 ms/op

Iteration   3: 5.139 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.985 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.491 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  27.629 ms/op
                 existUser·p0.9999: 33.285 ms/op
                 existUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189737
  mean =      5.056 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 118734 
    [ 5.000,  7.500) = 62579 
    [ 7.500, 10.000) = 6465 
    [10.000, 12.500) = 1318 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     24.840 ms/op
     p(99.9900) =     31.623 ms/op
     p(99.9990) =     35.104 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 17.740 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.982 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.138 ±(99.9%) 0.017 ms/op
Iteration   1: 5.355 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   8.241 ms/op
                 getUser·p0.99:   12.730 ms/op
                 getUser·p0.999:  25.011 ms/op
                 getUser·p0.9999: 30.541 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   2: 5.204 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.398 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  23.382 ms/op
                 getUser·p0.9999: 30.104 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 5.101 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.540 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  27.994 ms/op
                 getUser·p0.9999: 33.513 ms/op
                 getUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183833
  mean =      5.218 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 100793 
    [ 5.000,  7.500) = 73319 
    [ 7.500, 10.000) = 7105 
    [10.000, 12.500) = 1523 
    [12.500, 15.000) = 600 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     23.800 ms/op
     p(99.9900) =     32.264 ms/op
     p(99.9990) =     35.049 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 18.400 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 7.099 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.220 ±(99.9%) 0.023 ms/op
Iteration   1: 6.212 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.982 ms/op
                 listUser·p0.999:  30.053 ms/op
                 listUser·p0.9999: 40.931 ms/op
                 listUser·p1.00:   41.484 ms/op

Iteration   2: 6.283 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.910 ms/op
                 listUser·p0.99:   12.894 ms/op
                 listUser·p0.999:  25.368 ms/op
                 listUser·p0.9999: 27.916 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   3: 6.151 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  20.939 ms/op
                 listUser·p0.9999: 26.837 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154272
  mean =      6.215 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10242 
    [ 5.000, 10.000) = 140207 
    [10.000, 15.000) = 3229 
    [15.000, 20.000) = 301 
    [20.000, 25.000) = 119 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      7.406 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     12.222 ms/op
     p(99.9000) =     25.330 ms/op
     p(99.9900) =     39.565 ms/op
     p(99.9990) =     41.484 ms/op
     p(99.9999) =     41.484 ms/op
    p(100.0000) =     41.484 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.152 ± 4.173  ops/ms
ClientPb.existUser                       thrpt       3   6.520 ± 1.008  ops/ms
ClientPb.getUser                         thrpt       3   6.265 ± 1.102  ops/ms
ClientPb.listUser                        thrpt       3   5.254 ± 1.765  ops/ms
ClientPb.createUser                       avgt       3   5.089 ± 2.399   ms/op
ClientPb.existUser                        avgt       3   4.872 ± 1.234   ms/op
ClientPb.getUser                          avgt       3   5.278 ± 3.283   ms/op
ClientPb.listUser                         avgt       3   6.079 ± 4.156   ms/op
ClientPb.createUser                     sample  184797   5.188 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.585           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.907           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.537           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.847           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.851           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.783           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.140           ms/op
ClientPb.existUser                      sample  189737   5.056 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.994           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.840           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.623           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  183833   5.218 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.228           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.800           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.264           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.324           ms/op
ClientPb.listUser                       sample  154272   6.215 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.964           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.222           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.330           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.565           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.484           ms/op
