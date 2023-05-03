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
# Warmup Iteration   1: 1.766 ops/ms
# Warmup Iteration   2: 4.186 ops/ms
# Warmup Iteration   3: 7.237 ops/ms
Iteration   1: 7.223 ops/ms
Iteration   2: 8.259 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.944 ±(99.9%) 11.422 ops/ms [Average]
  (min, avg, max) = (7.223, 7.944, 8.349), stdev = 0.626
  CI (99.9%): [≈ 0, 19.365] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.329 ops/ms
# Warmup Iteration   2: 6.858 ops/ms
# Warmup Iteration   3: 8.193 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.479 ops/ms
Iteration   3: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.419 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (8.222, 8.419, 8.558), stdev = 0.176
  CI (99.9%): [5.211, 11.628] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 6.612 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 7.593 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.992 ±(99.9%) 6.292 ops/ms [Average]
  (min, avg, max) = (7.593, 7.992, 8.191), stdev = 0.345
  CI (99.9%): [1.700, 14.283] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.647 ops/ms
# Warmup Iteration   3: 6.460 ops/ms
Iteration   1: 6.928 ops/ms
Iteration   2: 6.967 ops/ms
Iteration   3: 6.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.941 ±(99.9%) 0.398 ops/ms [Average]
  (min, avg, max) = (6.928, 6.941, 6.967), stdev = 0.022
  CI (99.9%): [6.543, 7.340] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.073 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
Iteration   2: 3.892 ±(99.9%) 0.009 ms/op
Iteration   3: 3.918 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.931 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.892, 3.931, 3.983), stdev = 0.047
  CI (99.9%): [3.079, 4.783] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.699 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.003 ms/op
Iteration   1: 3.901 ±(99.9%) 0.006 ms/op
Iteration   2: 3.838 ±(99.9%) 0.003 ms/op
Iteration   3: 3.689 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.809 ±(99.9%) 1.990 ms/op [Average]
  (min, avg, max) = (3.689, 3.809, 3.901), stdev = 0.109
  CI (99.9%): [1.820, 5.799] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.631 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.006 ms/op
Iteration   1: 4.014 ±(99.9%) 0.008 ms/op
Iteration   2: 3.808 ±(99.9%) 0.007 ms/op
Iteration   3: 3.821 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.881 ±(99.9%) 2.105 ms/op [Average]
  (min, avg, max) = (3.808, 3.881, 4.014), stdev = 0.115
  CI (99.9%): [1.776, 5.986] (assumes normal distribution)


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
# Warmup Iteration   1: 14.204 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.665 ±(99.9%) 0.009 ms/op
Iteration   1: 4.570 ±(99.9%) 0.008 ms/op
Iteration   2: 4.517 ±(99.9%) 0.015 ms/op
Iteration   3: 4.596 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.561 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (4.517, 4.561, 4.596), stdev = 0.041
  CI (99.9%): [3.820, 5.302] (assumes normal distribution)


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
# Warmup Iteration   1: 12.225 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.528 ±(99.9%) 0.018 ms/op
Iteration   1: 3.904 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  23.138 ms/op
                 createUser·p0.9999: 29.538 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   2: 3.832 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  24.937 ms/op
                 createUser·p0.9999: 30.899 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   3: 3.918 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.806 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  26.345 ms/op
                 createUser·p0.9999: 34.516 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246988
  mean =      3.885 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 382 
    [ 2.500,  5.000) = 235793 
    [ 5.000,  7.500) = 8985 
    [ 7.500, 10.000) = 1077 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     33.453 ms/op
     p(99.9990) =     34.900 ms/op
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
# Warmup Iteration   1: 11.073 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
Iteration   1: 3.757 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   7.119 ms/op
                 existUser·p0.999:  20.571 ms/op
                 existUser·p0.9999: 28.114 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.703 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.561 ms/op
                 existUser·p0.999:  10.282 ms/op
                 existUser·p0.9999: 26.177 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.835 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  25.492 ms/op
                 existUser·p0.9999: 30.988 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254972
  mean =      3.764 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 505 
    [ 2.500,  5.000) = 246224 
    [ 5.000,  7.500) = 6433 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     29.868 ms/op
     p(99.9990) =     31.397 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 10.732 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.014 ms/op
Iteration   1: 4.052 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  18.121 ms/op
                 getUser·p0.9999: 28.649 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  25.183 ms/op
                 getUser·p0.9999: 27.687 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.974 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.976 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  10.607 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244833
  mean =      3.921 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 130 
    [ 2.500,  5.000) = 234175 
    [ 5.000,  7.500) = 8089 
    [ 7.500, 10.000) = 1760 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     18.033 ms/op
     p(99.9900) =     29.886 ms/op
     p(99.9990) =     31.901 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 14.966 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.070 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.709 ±(99.9%) 0.016 ms/op
Iteration   1: 4.704 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  25.757 ms/op
                 listUser·p0.9999: 27.992 ms/op
                 listUser·p1.00:   29.295 ms/op

Iteration   2: 4.675 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 22.648 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.586 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  15.894 ms/op
                 listUser·p0.9999: 19.826 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206001
  mean =      4.654 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 177332 
    [ 5.000,  7.500) = 24322 
    [ 7.500, 10.000) = 3258 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     27.145 ms/op
     p(99.9990) =     29.003 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.944 ± 11.422  ops/ms
ClientPb.existUser                       thrpt       3   8.419 ±  3.208  ops/ms
ClientPb.getUser                         thrpt       3   7.992 ±  6.292  ops/ms
ClientPb.listUser                        thrpt       3   6.941 ±  0.398  ops/ms
ClientPb.createUser                       avgt       3   3.931 ±  0.852   ms/op
ClientPb.existUser                        avgt       3   3.809 ±  1.990   ms/op
ClientPb.getUser                          avgt       3   3.881 ±  2.105   ms/op
ClientPb.listUser                         avgt       3   4.561 ±  0.741   ms/op
ClientPb.createUser                     sample  246988   3.885 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.270            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.334            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.858            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.988            ms/op
ClientPb.createUser:createUser·p0.999   sample          24.478            ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.453            ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931            ms/op
ClientPb.existUser                      sample  254972   3.764 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.092            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.530            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.791            ms/op
ClientPb.existUser:existUser·p0.999     sample          19.923            ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.868            ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850            ms/op
ClientPb.getUser                        sample  244833   3.921 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.397            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.740            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.479            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.033            ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.886            ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949            ms/op
ClientPb.listUser                       sample  206001   4.654 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.868            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.603            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847            ms/op
ClientPb.listUser:listUser·p0.999       sample          20.120            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.145            ms/op
ClientPb.listUser:listUser·p1.00        sample          29.295            ms/op
