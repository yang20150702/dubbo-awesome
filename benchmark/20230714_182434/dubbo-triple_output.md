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
# Warmup Iteration   1: 0.942 ops/ms
# Warmup Iteration   2: 1.990 ops/ms
# Warmup Iteration   3: 4.460 ops/ms
Iteration   1: 4.979 ops/ms
Iteration   2: 5.144 ops/ms
Iteration   3: 5.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.131 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (4.979, 5.131, 5.270), stdev = 0.146
  CI (99.9%): [2.463, 7.799] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.429 ops/ms
# Warmup Iteration   2: 4.261 ops/ms
# Warmup Iteration   3: 5.306 ops/ms
Iteration   1: 5.449 ops/ms
Iteration   2: 5.500 ops/ms
Iteration   3: 5.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.459 ±(99.9%) 0.670 ops/ms [Average]
  (min, avg, max) = (5.429, 5.459, 5.500), stdev = 0.037
  CI (99.9%): [4.790, 6.129] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.406 ops/ms
# Warmup Iteration   2: 3.520 ops/ms
# Warmup Iteration   3: 5.145 ops/ms
Iteration   1: 5.356 ops/ms
Iteration   2: 5.247 ops/ms
Iteration   3: 5.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.281 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (5.241, 5.281, 5.356), stdev = 0.065
  CI (99.9%): [4.104, 6.459] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.213 ops/ms
# Warmup Iteration   2: 2.866 ops/ms
# Warmup Iteration   3: 4.128 ops/ms
Iteration   1: 4.366 ops/ms
Iteration   2: 4.479 ops/ms
Iteration   3: 4.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.458 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (4.366, 4.458, 4.528), stdev = 0.083
  CI (99.9%): [2.938, 5.977] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:56
# Fork: 1 of 1
# Warmup Iteration   1: 21.418 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 7.857 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.631 ±(99.9%) 0.009 ms/op
Iteration   1: 6.002 ±(99.9%) 0.015 ms/op
Iteration   2: 6.053 ±(99.9%) 0.009 ms/op
Iteration   3: 5.726 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.927 ±(99.9%) 3.202 ms/op [Average]
  (min, avg, max) = (5.726, 5.927, 6.053), stdev = 0.176
  CI (99.9%): [2.725, 9.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.463 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.747 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.098 ±(99.9%) 0.014 ms/op
Iteration   1: 5.978 ±(99.9%) 0.009 ms/op
Iteration   2: 5.933 ±(99.9%) 0.012 ms/op
Iteration   3: 5.974 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.962 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (5.933, 5.962, 5.978), stdev = 0.025
  CI (99.9%): [5.506, 6.417] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 23.783 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 8.720 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.166 ±(99.9%) 0.013 ms/op
Iteration   1: 5.901 ±(99.9%) 0.015 ms/op
Iteration   2: 6.144 ±(99.9%) 0.007 ms/op
Iteration   3: 5.951 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.999 ±(99.9%) 2.343 ms/op [Average]
  (min, avg, max) = (5.901, 5.999, 6.144), stdev = 0.128
  CI (99.9%): [3.656, 8.342] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 23.769 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 9.333 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.291 ±(99.9%) 0.015 ms/op
Iteration   1: 7.128 ±(99.9%) 0.016 ms/op
Iteration   2: 6.953 ±(99.9%) 0.017 ms/op
Iteration   3: 6.950 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.010 ±(99.9%) 1.859 ms/op [Average]
  (min, avg, max) = (6.950, 7.010, 7.128), stdev = 0.102
  CI (99.9%): [5.151, 8.869] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 22.306 ±(99.9%) 0.414 ms/op
# Warmup Iteration   2: 8.175 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.542 ±(99.9%) 0.031 ms/op
Iteration   1: 6.131 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.318 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   8.086 ms/op
                 createUser·p0.95:   9.519 ms/op
                 createUser·p0.99:   12.523 ms/op
                 createUser·p0.999:  29.131 ms/op
                 createUser·p0.9999: 31.494 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   2: 5.811 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.724 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   11.768 ms/op
                 createUser·p0.999:  31.136 ms/op
                 createUser·p0.9999: 34.637 ms/op
                 createUser·p1.00:   34.931 ms/op

Iteration   3: 6.300 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   2.785 ms/op
                 createUser·p0.50:   5.718 ms/op
                 createUser·p0.90:   8.552 ms/op
                 createUser·p0.95:   10.224 ms/op
                 createUser·p0.99:   14.451 ms/op
                 createUser·p0.999:  30.769 ms/op
                 createUser·p0.9999: 38.006 ms/op
                 createUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157855
  mean =      6.074 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 26951 
    [ 5.000,  7.500) = 112319 
    [ 7.500, 10.000) = 12685 
    [10.000, 12.500) = 3930 
    [12.500, 15.000) = 1284 
    [15.000, 17.500) = 319 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 103 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      7.840 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     13.025 ms/op
     p(99.9000) =     30.147 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     38.170 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 21.219 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 7.287 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.123 ±(99.9%) 0.028 ms/op
Iteration   1: 6.099 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.486 ms/op
                 existUser·p0.50:   5.538 ms/op
                 existUser·p0.90:   8.487 ms/op
                 existUser·p0.95:   9.863 ms/op
                 existUser·p0.99:   12.616 ms/op
                 existUser·p0.999:  27.516 ms/op
                 existUser·p0.9999: 31.602 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   2: 5.793 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   5.423 ms/op
                 existUser·p0.90:   7.381 ms/op
                 existUser·p0.95:   8.569 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 43.775 ms/op
                 existUser·p1.00:   49.676 ms/op

Iteration   3: 6.220 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   5.636 ms/op
                 existUser·p0.90:   8.520 ms/op
                 existUser·p0.95:   9.994 ms/op
                 existUser·p0.99:   13.910 ms/op
                 existUser·p0.999:  31.425 ms/op
                 existUser·p0.9999: 38.273 ms/op
                 existUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 159077
  mean =      6.032 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 37942 
    [ 5.000, 10.000) = 115021 
    [10.000, 15.000) = 5528 
    [15.000, 20.000) = 421 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 54 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 38 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.552 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     27.144 ms/op
     p(99.9900) =     41.687 ms/op
     p(99.9990) =     49.638 ms/op
     p(99.9999) =     49.676 ms/op
    p(100.0000) =     49.676 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.654 ±(99.9%) 0.463 ms/op
# Warmup Iteration   2: 7.500 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.364 ±(99.9%) 0.030 ms/op
Iteration   1: 6.214 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   5.825 ms/op
                 getUser·p0.90:   7.815 ms/op
                 getUser·p0.95:   9.437 ms/op
                 getUser·p0.99:   12.812 ms/op
                 getUser·p0.999:  24.331 ms/op
                 getUser·p0.9999: 28.592 ms/op
                 getUser·p1.00:   40.567 ms/op

Iteration   2: 6.174 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   5.661 ms/op
                 getUser·p0.90:   8.266 ms/op
                 getUser·p0.95:   9.994 ms/op
                 getUser·p0.99:   13.238 ms/op
                 getUser·p0.999:  33.194 ms/op
                 getUser·p0.9999: 36.110 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 6.073 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.015 ms/op
                 getUser·p0.50:   5.677 ms/op
                 getUser·p0.90:   7.774 ms/op
                 getUser·p0.95:   9.355 ms/op
                 getUser·p0.99:   11.846 ms/op
                 getUser·p0.999:  20.591 ms/op
                 getUser·p0.9999: 30.268 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155816
  mean =      6.153 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 24637 
    [ 5.000, 10.000) = 124869 
    [10.000, 15.000) = 5755 
    [15.000, 20.000) = 315 
    [20.000, 25.000) = 101 
    [25.000, 30.000) = 64 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.954 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     12.616 ms/op
     p(99.9000) =     23.268 ms/op
     p(99.9900) =     35.745 ms/op
     p(99.9990) =     38.262 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


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
# Warmup Iteration   1: 23.912 ±(99.9%) 0.442 ms/op
# Warmup Iteration   2: 9.040 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 7.284 ±(99.9%) 0.038 ms/op
Iteration   1: 7.317 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   3.183 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   9.814 ms/op
                 listUser·p0.95:   11.272 ms/op
                 listUser·p0.99:   15.008 ms/op
                 listUser·p0.999:  32.604 ms/op
                 listUser·p0.9999: 38.552 ms/op
                 listUser·p1.00:   39.059 ms/op

Iteration   2: 7.419 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   6.816 ms/op
                 listUser·p0.90:   9.830 ms/op
                 listUser·p0.95:   11.403 ms/op
                 listUser·p0.99:   15.018 ms/op
                 listUser·p0.999:  39.649 ms/op
                 listUser·p0.9999: 47.714 ms/op
                 listUser·p1.00:   48.955 ms/op

Iteration   3: 7.262 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   6.750 ms/op
                 listUser·p0.90:   9.437 ms/op
                 listUser·p0.95:   11.158 ms/op
                 listUser·p0.99:   14.156 ms/op
                 listUser·p0.999:  30.701 ms/op
                 listUser·p0.9999: 34.222 ms/op
                 listUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 130881
  mean =      7.332 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1779 
    [ 5.000, 10.000) = 117510 
    [10.000, 15.000) = 10382 
    [15.000, 20.000) = 848 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 119 
    [35.000, 40.000) = 64 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.748 ms/op
     p(50.0000) =      6.742 ms/op
     p(90.0000) =      9.732 ms/op
     p(95.0000) =     11.272 ms/op
     p(99.0000) =     14.762 ms/op
     p(99.9000) =     33.394 ms/op
     p(99.9900) =     42.462 ms/op
     p(99.9990) =     48.834 ms/op
     p(99.9999) =     48.955 ms/op
    p(100.0000) =     48.955 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.131 ± 2.668  ops/ms
ClientPb.existUser                       thrpt       3   5.459 ± 0.670  ops/ms
ClientPb.getUser                         thrpt       3   5.281 ± 1.177  ops/ms
ClientPb.listUser                        thrpt       3   4.458 ± 1.519  ops/ms
ClientPb.createUser                       avgt       3   5.927 ± 3.202   ms/op
ClientPb.existUser                        avgt       3   5.962 ± 0.456   ms/op
ClientPb.getUser                          avgt       3   5.999 ± 2.343   ms/op
ClientPb.listUser                         avgt       3   7.010 ± 1.859   ms/op
ClientPb.createUser                     sample  157855   6.074 ± 0.016   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.318           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.840           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.454           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.025           ms/op
ClientPb.createUser:createUser·p0.999   sample          30.147           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.914           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.207           ms/op
ClientPb.existUser                      sample  159077   6.032 ± 0.016   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.692           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.90      sample           8.094           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.552           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.599           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.144           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          49.676           ms/op
ClientPb.getUser                        sample  155816   6.153 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.584           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.954           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.585           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.616           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.745           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.567           ms/op
ClientPb.listUser                       sample  130881   7.332 ± 0.021   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.748           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.732           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.272           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.762           ms/op
ClientPb.listUser:listUser·p0.999       sample          33.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.462           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.955           ms/op
