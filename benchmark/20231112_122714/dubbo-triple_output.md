# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.146 ops/ms
# Warmup Iteration   2: 5.028 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 8.467 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.570 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (8.467, 8.570, 8.725), stdev = 0.136
  CI (99.9%): [6.083, 11.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.464 ops/ms
# Warmup Iteration   2: 7.900 ops/ms
# Warmup Iteration   3: 8.815 ops/ms
Iteration   1: 8.928 ops/ms
Iteration   2: 8.834 ops/ms
Iteration   3: 8.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.723 ±(99.9%) 5.069 ops/ms [Average]
  (min, avg, max) = (8.407, 8.723, 8.928), stdev = 0.278
  CI (99.9%): [3.654, 13.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.604 ops/ms
# Warmup Iteration   2: 7.434 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.356 ops/ms
Iteration   2: 8.259 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.324 ±(99.9%) 1.036 ops/ms [Average]
  (min, avg, max) = (8.259, 8.324, 8.358), stdev = 0.057
  CI (99.9%): [7.289, 9.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.114 ops/ms
# Warmup Iteration   2: 6.662 ops/ms
# Warmup Iteration   3: 6.987 ops/ms
Iteration   1: 7.464 ops/ms
Iteration   2: 7.246 ops/ms
Iteration   3: 7.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.413 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (7.246, 7.413, 7.529), stdev = 0.148
  CI (99.9%): [4.709, 10.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.774 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.006 ms/op
Iteration   1: 3.824 ±(99.9%) 0.003 ms/op
Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
Iteration   3: 3.814 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.780 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (3.704, 3.780, 3.824), stdev = 0.067
  CI (99.9%): [2.567, 4.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.037 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.006 ms/op
Iteration   1: 3.592 ±(99.9%) 0.003 ms/op
Iteration   2: 3.673 ±(99.9%) 0.005 ms/op
Iteration   3: 3.678 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.648 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.592, 3.648, 3.678), stdev = 0.048
  CI (99.9%): [2.766, 4.529] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.682 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.004 ms/op
Iteration   1: 3.742 ±(99.9%) 0.005 ms/op
Iteration   2: 3.639 ±(99.9%) 0.007 ms/op
Iteration   3: 3.806 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.729 ±(99.9%) 1.536 ms/op [Average]
  (min, avg, max) = (3.639, 3.729, 3.806), stdev = 0.084
  CI (99.9%): [2.193, 5.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.386 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.427 ±(99.9%) 0.009 ms/op
Iteration   1: 4.465 ±(99.9%) 0.010 ms/op
Iteration   2: 4.295 ±(99.9%) 0.011 ms/op
Iteration   3: 4.392 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.384 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (4.295, 4.384, 4.465), stdev = 0.085
  CI (99.9%): [2.829, 5.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.283 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.015 ms/op
Iteration   1: 3.672 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  9.004 ms/op
                 createUser·p0.9999: 24.356 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.914 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 28.955 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   3: 3.941 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.413 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  25.521 ms/op
                 createUser·p0.9999: 30.634 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250072
  mean =      3.838 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1616 
    [ 2.500,  5.000) = 239450 
    [ 5.000,  7.500) = 7120 
    [ 7.500, 10.000) = 1269 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.349 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.751 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.011 ms/op
Iteration   1: 3.579 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.515 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  11.676 ms/op
                 existUser·p0.9999: 21.924 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.574 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  21.056 ms/op
                 existUser·p0.9999: 24.510 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.826 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  15.286 ms/op
                 existUser·p0.9999: 27.010 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 262355
  mean =      3.656 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2955 
    [ 2.500,  5.000) = 250963 
    [ 5.000,  7.500) = 6836 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.183 ms/op
     p(99.9900) =     26.141 ms/op
     p(99.9990) =     27.710 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.822 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
Iteration   1: 3.943 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  17.379 ms/op
                 getUser·p0.9999: 27.567 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 3.643 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  22.788 ms/op
                 getUser·p0.9999: 26.654 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 3.728 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  14.057 ms/op
                 getUser·p0.9999: 29.442 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254983
  mean =      3.767 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2054 
    [ 2.500,  5.000) = 242553 
    [ 5.000,  7.500) = 7025 
    [ 7.500, 10.000) = 2709 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     29.947 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.260 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.720 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.015 ms/op
Iteration   1: 4.446 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  25.002 ms/op
                 listUser·p0.9999: 30.992 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 4.516 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.051 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.027 ms/op
                 listUser·p0.9999: 18.027 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.396 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  15.847 ms/op
                 listUser·p0.9999: 18.201 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 215592
  mean =      4.452 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 194939 
    [ 5.000,  7.500) = 17779 
    [ 7.500, 10.000) = 1878 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.980 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     26.447 ms/op
     p(99.9990) =     32.430 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.570 ± 2.487  ops/ms
ClientPb.existUser                       thrpt       3   8.723 ± 5.069  ops/ms
ClientPb.getUser                         thrpt       3   8.324 ± 1.036  ops/ms
ClientPb.listUser                        thrpt       3   7.413 ± 2.704  ops/ms
ClientPb.createUser                       avgt       3   3.780 ± 1.214   ms/op
ClientPb.existUser                        avgt       3   3.648 ± 0.882   ms/op
ClientPb.getUser                          avgt       3   3.729 ± 1.536   ms/op
ClientPb.listUser                         avgt       3   4.384 ± 1.556   ms/op
ClientPb.createUser                     sample  250072   3.838 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.899           ms/op
ClientPb.existUser                      sample  262355   3.656 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.612           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.183           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.141           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.886           ms/op
ClientPb.getUser                        sample  254983   3.767 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.520           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.876           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.475           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  215592   4.452 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.957           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.447           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.539           ms/op
