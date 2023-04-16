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
# Warmup Iteration   1: 1.641 ops/ms
# Warmup Iteration   2: 3.811 ops/ms
# Warmup Iteration   3: 7.455 ops/ms
Iteration   1: 7.622 ops/ms
Iteration   2: 7.991 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.867 ±(99.9%) 3.866 ops/ms [Average]
  (min, avg, max) = (7.622, 7.867, 7.991), stdev = 0.212
  CI (99.9%): [4.000, 11.733] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.297 ops/ms
# Warmup Iteration   2: 6.864 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.291 ops/ms
Iteration   2: 8.166 ops/ms
Iteration   3: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.323 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (8.166, 8.323, 8.510), stdev = 0.174
  CI (99.9%): [5.148, 11.498] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.961 ops/ms
# Warmup Iteration   2: 6.412 ops/ms
# Warmup Iteration   3: 7.609 ops/ms
Iteration   1: 8.203 ops/ms
Iteration   2: 7.762 ops/ms
Iteration   3: 8.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.110 ±(99.9%) 5.697 ops/ms [Average]
  (min, avg, max) = (7.762, 8.110, 8.365), stdev = 0.312
  CI (99.9%): [2.413, 13.807] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.134 ops/ms
# Warmup Iteration   2: 5.887 ops/ms
# Warmup Iteration   3: 6.690 ops/ms
Iteration   1: 6.959 ops/ms
Iteration   2: 6.801 ops/ms
Iteration   3: 6.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.824 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (6.711, 6.824, 6.959), stdev = 0.125
  CI (99.9%): [4.540, 9.108] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.056 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.013 ms/op
Iteration   1: 3.986 ±(99.9%) 0.014 ms/op
Iteration   2: 4.217 ±(99.9%) 0.007 ms/op
Iteration   3: 3.921 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.041 ±(99.9%) 2.835 ms/op [Average]
  (min, avg, max) = (3.921, 4.041, 4.217), stdev = 0.155
  CI (99.9%): [1.206, 6.877] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.994 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.013 ms/op
Iteration   1: 3.868 ±(99.9%) 0.007 ms/op
Iteration   2: 3.737 ±(99.9%) 0.014 ms/op
Iteration   3: 3.730 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.778 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (3.730, 3.778, 3.868), stdev = 0.078
  CI (99.9%): [2.361, 5.196] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.413 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.008 ms/op
Iteration   1: 3.946 ±(99.9%) 0.012 ms/op
Iteration   2: 3.850 ±(99.9%) 0.013 ms/op
Iteration   3: 3.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.930 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.850, 3.930, 3.992), stdev = 0.073
  CI (99.9%): [2.606, 5.253] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.605 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.380 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.972 ±(99.9%) 0.009 ms/op
Iteration   1: 4.743 ±(99.9%) 0.008 ms/op
Iteration   2: 4.557 ±(99.9%) 0.013 ms/op
Iteration   3: 4.546 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.615 ±(99.9%) 2.023 ms/op [Average]
  (min, avg, max) = (4.546, 4.615, 4.743), stdev = 0.111
  CI (99.9%): [2.592, 6.639] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.127 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.621 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.017 ms/op
Iteration   1: 4.143 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.915 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 31.410 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   2: 3.910 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  24.918 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 4.307 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.109 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   14.913 ms/op
                 createUser·p0.999:  23.518 ms/op
                 createUser·p0.9999: 31.705 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233237
  mean =      4.114 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 197 
    [ 2.500,  5.000) = 215186 
    [ 5.000,  7.500) = 15166 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 362 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     23.677 ms/op
     p(99.9900) =     31.338 ms/op
     p(99.9990) =     33.107 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.551 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
Iteration   1: 3.839 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  22.863 ms/op
                 existUser·p0.9999: 25.188 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.880 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  13.615 ms/op
                 existUser·p0.9999: 28.058 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.907 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.960 ms/op
                 existUser·p0.99:   6.761 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 29.819 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247640
  mean =      3.875 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 237378 
    [ 5.000,  7.500) = 8019 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     13.572 ms/op
     p(99.9900) =     28.196 ms/op
     p(99.9990) =     30.218 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.983 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.014 ms/op
Iteration   1: 4.123 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  13.200 ms/op
                 getUser·p0.9999: 27.009 ms/op
                 getUser·p1.00:   32.866 ms/op

Iteration   2: 3.948 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  25.985 ms/op
                 getUser·p0.9999: 33.646 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   3: 4.042 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.479 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  13.039 ms/op
                 getUser·p0.9999: 32.615 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237741
  mean =      4.036 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 225773 
    [ 5.000,  7.500) = 9305 
    [ 7.500, 10.000) = 1773 
    [10.000, 12.500) = 414 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     15.603 ms/op
     p(99.9900) =     32.619 ms/op
     p(99.9990) =     34.685 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.139 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.464 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.863 ±(99.9%) 0.018 ms/op
Iteration   1: 4.717 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.802 ms/op
                 listUser·p0.99:   8.425 ms/op
                 listUser·p0.999:  25.763 ms/op
                 listUser·p0.9999: 28.272 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   2: 4.916 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.642 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  22.446 ms/op
                 listUser·p0.9999: 29.376 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   3: 4.736 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.163 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200502
  mean =      4.788 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 166360 
    [ 5.000,  7.500) = 28792 
    [ 7.500, 10.000) = 3952 
    [10.000, 12.500) = 625 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     28.507 ms/op
     p(99.9990) =     29.850 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.867 ± 3.866  ops/ms
ClientPb.existUser                       thrpt       3   8.323 ± 3.175  ops/ms
ClientPb.getUser                         thrpt       3   8.110 ± 5.697  ops/ms
ClientPb.listUser                        thrpt       3   6.824 ± 2.284  ops/ms
ClientPb.createUser                       avgt       3   4.041 ± 2.835   ms/op
ClientPb.existUser                        avgt       3   3.778 ± 1.418   ms/op
ClientPb.getUser                          avgt       3   3.930 ± 1.323   ms/op
ClientPb.listUser                         avgt       3   4.615 ± 2.023   ms/op
ClientPb.createUser                     sample  233237   4.114 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.423           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.028           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.338           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  247640   3.875 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.572           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.196           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.441           ms/op
ClientPb.getUser                        sample  237741   4.036 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.548           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.603           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.619           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  200502   4.788 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.627           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.507           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.983           ms/op
