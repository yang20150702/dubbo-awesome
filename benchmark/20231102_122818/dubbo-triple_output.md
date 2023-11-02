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
# Warmup Iteration   1: 1.696 ops/ms
# Warmup Iteration   2: 4.112 ops/ms
# Warmup Iteration   3: 7.412 ops/ms
Iteration   1: 7.687 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.958 ±(99.9%) 4.724 ops/ms [Average]
  (min, avg, max) = (7.687, 7.958, 8.203), stdev = 0.259
  CI (99.9%): [3.234, 12.682] (assumes normal distribution)


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
# Warmup Iteration   1: 2.646 ops/ms
# Warmup Iteration   2: 7.278 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.338 ops/ms
Iteration   2: 8.485 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.446 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (8.338, 8.446, 8.514), stdev = 0.094
  CI (99.9%): [6.725, 10.166] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.039 ops/ms
# Warmup Iteration   2: 6.834 ops/ms
# Warmup Iteration   3: 7.802 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.013 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (7.942, 8.013, 8.074), stdev = 0.066
  CI (99.9%): [6.803, 9.222] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.236 ops/ms
# Warmup Iteration   2: 5.678 ops/ms
# Warmup Iteration   3: 6.580 ops/ms
Iteration   1: 6.763 ops/ms
Iteration   2: 6.759 ops/ms
Iteration   3: 6.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.812 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (6.759, 6.812, 6.913), stdev = 0.088
  CI (99.9%): [5.207, 8.417] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.156 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.004 ms/op
Iteration   1: 4.042 ±(99.9%) 0.004 ms/op
Iteration   2: 3.997 ±(99.9%) 0.005 ms/op
Iteration   3: 4.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.036 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.997, 4.036, 4.068), stdev = 0.036
  CI (99.9%): [3.381, 4.690] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.932 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.003 ms/op
Iteration   1: 3.914 ±(99.9%) 0.004 ms/op
Iteration   2: 3.783 ±(99.9%) 0.004 ms/op
Iteration   3: 3.952 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.883 ±(99.9%) 1.615 ms/op [Average]
  (min, avg, max) = (3.783, 3.883, 3.952), stdev = 0.089
  CI (99.9%): [2.268, 5.498] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.775 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.004 ms/op
Iteration   1: 4.104 ±(99.9%) 0.005 ms/op
Iteration   2: 4.023 ±(99.9%) 0.004 ms/op
Iteration   3: 4.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.082 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (4.023, 4.082, 4.118), stdev = 0.051
  CI (99.9%): [3.153, 5.010] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.107 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.375 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.847 ±(99.9%) 0.006 ms/op
Iteration   1: 4.717 ±(99.9%) 0.008 ms/op
Iteration   2: 4.705 ±(99.9%) 0.009 ms/op
Iteration   3: 4.792 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.738 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (4.705, 4.738, 4.792), stdev = 0.047
  CI (99.9%): [3.880, 5.596] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.519 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.017 ms/op
Iteration   1: 4.015 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  24.084 ms/op
                 createUser·p0.9999: 25.986 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 4.080 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  24.882 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  13.189 ms/op
                 createUser·p0.9999: 30.779 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236519
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 283 
    [ 2.500,  5.000) = 223748 
    [ 5.000,  7.500) = 10916 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     29.022 ms/op
     p(99.9990) =     31.847 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.074 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
Iteration   1: 3.901 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  22.315 ms/op
                 existUser·p0.9999: 38.771 ms/op
                 existUser·p1.00:   39.649 ms/op

Iteration   2: 3.861 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 26.270 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.809 ms/op
                 existUser·p0.999:  25.657 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246801
  mean =      3.890 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 373 
    [ 2.500,  5.000) = 237898 
    [ 5.000,  7.500) = 7074 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     21.830 ms/op
     p(99.9900) =     36.870 ms/op
     p(99.9990) =     39.492 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 12.593 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.014 ms/op
Iteration   1: 4.041 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  10.666 ms/op
                 getUser·p0.9999: 22.091 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  21.556 ms/op
                 getUser·p0.9999: 24.346 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 4.051 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  16.973 ms/op
                 getUser·p0.9999: 25.408 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238361
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 227973 
    [ 5.000,  7.500) = 8529 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     17.159 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.217 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 14.115 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.410 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.915 ±(99.9%) 0.016 ms/op
Iteration   1: 4.907 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  24.952 ms/op
                 listUser·p0.9999: 26.932 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 4.768 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  18.492 ms/op
                 listUser·p0.9999: 25.077 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.685 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 19.024 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200572
  mean =      4.785 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 156881 
    [ 5.000,  7.500) = 39793 
    [ 7.500, 10.000) = 2781 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 313 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      2.048 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     26.409 ms/op
     p(99.9990) =     27.721 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.958 ± 4.724  ops/ms
ClientPb.existUser                       thrpt       3   8.446 ± 1.720  ops/ms
ClientPb.getUser                         thrpt       3   8.013 ± 1.209  ops/ms
ClientPb.listUser                        thrpt       3   6.812 ± 1.605  ops/ms
ClientPb.createUser                       avgt       3   4.036 ± 0.654   ms/op
ClientPb.existUser                        avgt       3   3.883 ± 1.615   ms/op
ClientPb.getUser                          avgt       3   4.082 ± 0.928   ms/op
ClientPb.listUser                         avgt       3   4.738 ± 0.858   ms/op
ClientPb.createUser                     sample  236519   4.058 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.640           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.022           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  246801   3.890 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.516           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.830           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.870           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.649           ms/op
ClientPb.getUser                        sample  238361   4.027 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.102           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.159           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968           ms/op
ClientPb.listUser                       sample  200572   4.785 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.048           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.579           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.409           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.754           ms/op
