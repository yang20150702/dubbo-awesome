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
# Warmup Iteration   1: 1.795 ops/ms
# Warmup Iteration   2: 4.166 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 7.477 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.007 ±(99.9%) 9.613 ops/ms [Average]
  (min, avg, max) = (7.477, 8.007, 8.530), stdev = 0.527
  CI (99.9%): [≈ 0, 17.620] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.458 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 8.597 ops/ms
Iteration   1: 8.579 ops/ms
Iteration   2: 8.781 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.643 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (8.570, 8.643, 8.781), stdev = 0.119
  CI (99.9%): [6.467, 10.819] (assumes normal distribution)


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
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 7.080 ops/ms
# Warmup Iteration   3: 7.942 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.034 ops/ms
Iteration   3: 7.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.003 ±(99.9%) 0.509 ops/ms [Average]
  (min, avg, max) = (7.981, 8.003, 8.034), stdev = 0.028
  CI (99.9%): [7.494, 8.512] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.375 ops/ms
# Warmup Iteration   2: 6.005 ops/ms
# Warmup Iteration   3: 6.809 ops/ms
Iteration   1: 7.047 ops/ms
Iteration   2: 6.823 ops/ms
Iteration   3: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.931 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (6.823, 6.931, 7.047), stdev = 0.112
  CI (99.9%): [4.882, 8.979] (assumes normal distribution)


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
# Warmup Iteration   1: 12.647 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.005 ms/op
Iteration   1: 4.070 ±(99.9%) 0.006 ms/op
Iteration   2: 3.906 ±(99.9%) 0.011 ms/op
Iteration   3: 3.909 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.961 ±(99.9%) 1.715 ms/op [Average]
  (min, avg, max) = (3.906, 3.961, 4.070), stdev = 0.094
  CI (99.9%): [2.247, 5.676] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.057 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.012 ms/op
Iteration   1: 3.707 ±(99.9%) 0.015 ms/op
Iteration   2: 3.766 ±(99.9%) 0.007 ms/op
Iteration   3: 3.683 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.718 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.683, 3.718, 3.766), stdev = 0.043
  CI (99.9%): [2.938, 4.499] (assumes normal distribution)


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
# Warmup Iteration   1: 12.208 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
Iteration   1: 4.029 ±(99.9%) 0.006 ms/op
Iteration   2: 4.070 ±(99.9%) 0.007 ms/op
Iteration   3: 3.940 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.013 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (3.940, 4.013, 4.070), stdev = 0.066
  CI (99.9%): [2.806, 5.220] (assumes normal distribution)


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
# Warmup Iteration   1: 13.548 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.361 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.015 ms/op
Iteration   1: 4.511 ±(99.9%) 0.015 ms/op
Iteration   2: 4.556 ±(99.9%) 0.013 ms/op
Iteration   3: 4.482 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.516 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (4.482, 4.516, 4.556), stdev = 0.038
  CI (99.9%): [3.831, 5.202] (assumes normal distribution)


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
# Warmup Iteration   1: 11.832 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.017 ms/op
Iteration   1: 4.045 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.672 ms/op
                 createUser·p0.999:  21.686 ms/op
                 createUser·p0.9999: 23.957 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.871 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  13.648 ms/op
                 createUser·p0.9999: 25.944 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 3.907 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 34.341 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243533
  mean =      3.940 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 676 
    [ 2.500,  5.000) = 228254 
    [ 5.000,  7.500) = 12710 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     21.478 ms/op
     p(99.9900) =     32.953 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.846 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.011 ms/op
Iteration   1: 3.817 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  9.636 ms/op
                 existUser·p0.9999: 24.268 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   2: 3.762 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  24.150 ms/op
                 existUser·p0.9999: 26.477 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.681 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  12.162 ms/op
                 existUser·p0.9999: 31.790 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255704
  mean =      3.753 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 843 
    [ 2.500,  5.000) = 246075 
    [ 5.000,  7.500) = 7701 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     12.080 ms/op
     p(99.9900) =     30.676 ms/op
     p(99.9990) =     32.527 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 11.717 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.628 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.014 ms/op
Iteration   1: 4.044 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   7.930 ms/op
                 getUser·p0.999:  21.788 ms/op
                 getUser·p0.9999: 24.379 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.858 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.898 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  25.270 ms/op
                 getUser·p0.9999: 29.419 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243943
  mean =      3.932 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 118 
    [ 2.500,  5.000) = 235101 
    [ 5.000,  7.500) = 6193 
    [ 7.500, 10.000) = 1990 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     21.631 ms/op
     p(99.9900) =     28.528 ms/op
     p(99.9990) =     29.837 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 13.066 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.118 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.014 ms/op
Iteration   1: 4.654 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  21.770 ms/op
                 listUser·p0.9999: 25.465 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 4.472 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  16.351 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.693 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.568 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 17.970 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208159
  mean =      4.604 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 179867 
    [ 5.000,  7.500) = 24348 
    [ 7.500, 10.000) = 2948 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     24.049 ms/op
     p(99.9990) =     26.354 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.007 ± 9.613  ops/ms
ClientPb.existUser                       thrpt       3   8.643 ± 2.176  ops/ms
ClientPb.getUser                         thrpt       3   8.003 ± 0.509  ops/ms
ClientPb.listUser                        thrpt       3   6.931 ± 2.049  ops/ms
ClientPb.createUser                       avgt       3   3.961 ± 1.715   ms/op
ClientPb.existUser                        avgt       3   3.718 ± 0.780   ms/op
ClientPb.getUser                          avgt       3   4.013 ± 1.207   ms/op
ClientPb.listUser                         avgt       3   4.516 ± 0.685   ms/op
ClientPb.createUser                     sample  243533   3.940 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.478           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.953           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931           ms/op
ClientPb.existUser                      sample  255704   3.753 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.616           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.080           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.676           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  243943   3.932 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.358           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.631           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.528           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  208159   4.604 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.400           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.049           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.608           ms/op
