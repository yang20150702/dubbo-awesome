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
# Warmup Iteration   1: 1.421 ops/ms
# Warmup Iteration   2: 3.420 ops/ms
# Warmup Iteration   3: 6.688 ops/ms
Iteration   1: 7.462 ops/ms
Iteration   2: 7.590 ops/ms
Iteration   3: 7.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.580 ±(99.9%) 2.051 ops/ms [Average]
  (min, avg, max) = (7.462, 7.580, 7.686), stdev = 0.112
  CI (99.9%): [5.529, 9.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.322 ops/ms
# Warmup Iteration   2: 6.803 ops/ms
# Warmup Iteration   3: 7.835 ops/ms
Iteration   1: 8.350 ops/ms
Iteration   2: 8.277 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.234 ±(99.9%) 2.588 ops/ms [Average]
  (min, avg, max) = (8.076, 8.234, 8.350), stdev = 0.142
  CI (99.9%): [5.646, 10.822] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 6.532 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 7.815 ops/ms
Iteration   2: 7.419 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.675 ±(99.9%) 4.054 ops/ms [Average]
  (min, avg, max) = (7.419, 7.675, 7.815), stdev = 0.222
  CI (99.9%): [3.621, 11.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 4.915 ops/ms
# Warmup Iteration   3: 6.576 ops/ms
Iteration   1: 6.652 ops/ms
Iteration   2: 6.650 ops/ms
Iteration   3: 6.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.685 ±(99.9%) 1.060 ops/ms [Average]
  (min, avg, max) = (6.650, 6.685, 6.752), stdev = 0.058
  CI (99.9%): [5.625, 7.744] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.597 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.513 ±(99.9%) 0.009 ms/op
Iteration   1: 4.081 ±(99.9%) 0.010 ms/op
Iteration   2: 4.071 ±(99.9%) 0.004 ms/op
Iteration   3: 4.008 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.053 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (4.008, 4.053, 4.081), stdev = 0.039
  CI (99.9%): [3.339, 4.768] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.959 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.009 ms/op
Iteration   1: 3.884 ±(99.9%) 0.008 ms/op
Iteration   2: 3.942 ±(99.9%) 0.004 ms/op
Iteration   3: 3.804 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.876 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (3.804, 3.876, 3.942), stdev = 0.069
  CI (99.9%): [2.617, 5.136] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.098 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.008 ms/op
Iteration   1: 4.353 ±(99.9%) 0.006 ms/op
Iteration   2: 4.047 ±(99.9%) 0.007 ms/op
Iteration   3: 4.064 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.155 ±(99.9%) 3.140 ms/op [Average]
  (min, avg, max) = (4.047, 4.155, 4.353), stdev = 0.172
  CI (99.9%): [1.014, 7.295] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.715 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.764 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.011 ms/op
Iteration   1: 4.722 ±(99.9%) 0.013 ms/op
Iteration   2: 4.618 ±(99.9%) 0.016 ms/op
Iteration   3: 4.771 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.703 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (4.618, 4.703, 4.771), stdev = 0.078
  CI (99.9%): [3.279, 6.128] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.432 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.265 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.642 ±(99.9%) 0.022 ms/op
Iteration   1: 4.175 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 26.826 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   2: 4.126 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.380 ms/op
                 createUser·p0.999:  26.299 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.412 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  10.800 ms/op
                 createUser·p0.9999: 32.782 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231914
  mean =      4.136 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 335 
    [ 2.500,  5.000) = 215008 
    [ 5.000,  7.500) = 14139 
    [ 7.500, 10.000) = 1906 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     31.557 ms/op
     p(99.9990) =     33.252 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 13.793 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.774 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
Iteration   1: 4.265 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   8.454 ms/op
                 existUser·p0.999:  14.467 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  20.360 ms/op
                 existUser·p0.9999: 28.639 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 4.045 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.782 ms/op
                 existUser·p0.999:  24.182 ms/op
                 existUser·p0.9999: 29.567 ms/op
                 existUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235652
  mean =      4.070 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189 
    [ 2.500,  5.000) = 220583 
    [ 5.000,  7.500) = 12239 
    [ 7.500, 10.000) = 1702 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     20.536 ms/op
     p(99.9900) =     28.944 ms/op
     p(99.9990) =     30.495 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 15.233 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.658 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.412 ±(99.9%) 0.016 ms/op
Iteration   1: 4.307 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   9.765 ms/op
                 getUser·p0.999:  16.073 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   2: 4.236 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  27.165 ms/op
                 getUser·p0.9999: 31.236 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   3: 3.990 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.703 ms/op
                 getUser·p0.999:  29.364 ms/op
                 getUser·p0.9999: 32.735 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229914
  mean =      4.173 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 213744 
    [ 5.000,  7.500) = 11298 
    [ 7.500, 10.000) = 3319 
    [10.000, 12.500) = 978 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     25.496 ms/op
     p(99.9900) =     31.753 ms/op
     p(99.9990) =     33.168 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 15.872 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 5.711 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.929 ±(99.9%) 0.017 ms/op
Iteration   1: 4.750 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   8.354 ms/op
                 listUser·p0.999:  26.345 ms/op
                 listUser·p0.9999: 27.730 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 4.906 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  19.548 ms/op
                 listUser·p0.9999: 24.732 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 4.870 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  18.335 ms/op
                 listUser·p0.9999: 22.717 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198266
  mean =      4.841 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 154591 
    [ 5.000,  7.500) = 39433 
    [ 7.500, 10.000) = 3239 
    [10.000, 12.500) = 467 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 114 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     22.601 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     29.661 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.580 ± 2.051  ops/ms
ClientPb.existUser                       thrpt       3   8.234 ± 2.588  ops/ms
ClientPb.getUser                         thrpt       3   7.675 ± 4.054  ops/ms
ClientPb.listUser                        thrpt       3   6.685 ± 1.060  ops/ms
ClientPb.createUser                       avgt       3   4.053 ± 0.714   ms/op
ClientPb.existUser                        avgt       3   3.876 ± 1.259   ms/op
ClientPb.getUser                          avgt       3   4.155 ± 3.140   ms/op
ClientPb.listUser                         avgt       3   4.703 ± 1.425   ms/op
ClientPb.createUser                     sample  231914   4.136 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.412           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.594           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.792           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.557           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.358           ms/op
ClientPb.existUser                      sample  235652   4.070 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.794           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.709           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.536           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.944           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.162           ms/op
ClientPb.getUser                        sample  229914   4.173 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.962           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.753           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  198266   4.841 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.737           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.263           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.983           ms/op
