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
# Warmup Iteration   1: 1.593 ops/ms
# Warmup Iteration   2: 3.541 ops/ms
# Warmup Iteration   3: 6.982 ops/ms
Iteration   1: 7.561 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 7.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.759 ±(99.9%) 3.715 ops/ms [Average]
  (min, avg, max) = (7.561, 7.759, 7.968), stdev = 0.204
  CI (99.9%): [4.043, 11.474] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 6.988 ops/ms
# Warmup Iteration   3: 7.666 ops/ms
Iteration   1: 8.506 ops/ms
Iteration   2: 8.387 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.352 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (8.163, 8.352, 8.506), stdev = 0.174
  CI (99.9%): [5.177, 11.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.916 ops/ms
# Warmup Iteration   2: 5.710 ops/ms
# Warmup Iteration   3: 7.312 ops/ms
Iteration   1: 7.887 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 7.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.833 ±(99.9%) 4.838 ops/ms [Average]
  (min, avg, max) = (7.545, 7.833, 8.067), stdev = 0.265
  CI (99.9%): [2.995, 12.670] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.960 ops/ms
# Warmup Iteration   2: 5.189 ops/ms
# Warmup Iteration   3: 6.541 ops/ms
Iteration   1: 6.588 ops/ms
Iteration   2: 6.397 ops/ms
Iteration   3: 6.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.508 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (6.397, 6.508, 6.588), stdev = 0.099
  CI (99.9%): [4.700, 8.317] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.228 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.006 ms/op
Iteration   1: 4.110 ±(99.9%) 0.004 ms/op
Iteration   2: 4.087 ±(99.9%) 0.004 ms/op
Iteration   3: 4.177 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.125 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (4.087, 4.125, 4.177), stdev = 0.047
  CI (99.9%): [3.269, 4.981] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.513 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.009 ms/op
Iteration   1: 3.903 ±(99.9%) 0.008 ms/op
Iteration   2: 3.946 ±(99.9%) 0.006 ms/op
Iteration   3: 3.780 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.876 ±(99.9%) 1.564 ms/op [Average]
  (min, avg, max) = (3.780, 3.876, 3.946), stdev = 0.086
  CI (99.9%): [2.312, 5.440] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.487 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.010 ms/op
Iteration   1: 4.146 ±(99.9%) 0.008 ms/op
Iteration   2: 4.090 ±(99.9%) 0.012 ms/op
Iteration   3: 4.061 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.099 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (4.061, 4.099, 4.146), stdev = 0.044
  CI (99.9%): [3.303, 4.895] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.428 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.558 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.913 ±(99.9%) 0.006 ms/op
Iteration   1: 4.728 ±(99.9%) 0.012 ms/op
Iteration   2: 4.762 ±(99.9%) 0.012 ms/op
Iteration   3: 4.733 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.741 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (4.728, 4.741, 4.762), stdev = 0.018
  CI (99.9%): [4.409, 5.073] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.302 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 5.014 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.021 ms/op
Iteration   1: 4.049 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  19.610 ms/op
                 createUser·p0.9999: 27.371 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 4.050 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  25.594 ms/op
                 createUser·p0.9999: 29.302 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   3: 4.094 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  15.758 ms/op
                 createUser·p0.9999: 37.445 ms/op
                 createUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236084
  mean =      4.065 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 161 
    [ 2.500,  5.000) = 220419 
    [ 5.000,  7.500) = 12881 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     20.624 ms/op
     p(99.9900) =     35.808 ms/op
     p(99.9990) =     37.725 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 11.523 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.160 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.015 ms/op
Iteration   1: 3.934 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.823 ms/op
                 existUser·p0.999:  12.878 ms/op
                 existUser·p0.9999: 29.061 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   2: 3.963 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  26.013 ms/op
                 existUser·p0.9999: 36.630 ms/op
                 existUser·p1.00:   38.666 ms/op

Iteration   3: 3.992 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.915 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   5.040 ms/op
                 existUser·p0.99:   8.372 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 37.420 ms/op
                 existUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242109
  mean =      3.963 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 228190 
    [ 5.000,  7.500) = 10472 
    [ 7.500, 10.000) = 2235 
    [10.000, 12.500) = 594 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     16.774 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     38.501 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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
# Warmup Iteration   1: 12.620 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.012 ms/op
Iteration   1: 4.165 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   6.554 ms/op
                 getUser·p0.99:   8.946 ms/op
                 getUser·p0.999:  23.270 ms/op
                 getUser·p0.9999: 25.700 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  14.392 ms/op
                 getUser·p0.9999: 27.148 ms/op
                 getUser·p1.00:   31.621 ms/op

Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  12.625 ms/op
                 getUser·p0.9999: 29.990 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232235
  mean =      4.132 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 216040 
    [ 5.000,  7.500) = 11953 
    [ 7.500, 10.000) = 3183 
    [10.000, 12.500) = 657 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     28.927 ms/op
     p(99.9990) =     31.301 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 15.003 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.114 ±(99.9%) 0.021 ms/op
Iteration   1: 4.868 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   9.685 ms/op
                 listUser·p0.999:  25.723 ms/op
                 listUser·p0.9999: 27.900 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 4.806 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  24.959 ms/op
                 listUser·p0.9999: 33.643 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   3: 4.883 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.925 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  21.758 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197588
  mean =      4.852 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 149029 
    [ 5.000,  7.500) = 41951 
    [ 7.500, 10.000) = 4989 
    [10.000, 12.500) = 883 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     33.951 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.759 ± 3.715  ops/ms
ClientPb.existUser                       thrpt       3   8.352 ± 3.175  ops/ms
ClientPb.getUser                         thrpt       3   7.833 ± 4.838  ops/ms
ClientPb.listUser                        thrpt       3   6.508 ± 1.808  ops/ms
ClientPb.createUser                       avgt       3   4.125 ± 0.856   ms/op
ClientPb.existUser                        avgt       3   3.876 ± 1.564   ms/op
ClientPb.getUser                          avgt       3   4.099 ± 0.796   ms/op
ClientPb.listUser                         avgt       3   4.741 ± 0.332   ms/op
ClientPb.createUser                     sample  236084   4.065 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.305           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.624           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.808           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.814           ms/op
ClientPb.existUser                      sample  242109   3.963 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.464           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.946           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.774           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.569           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.666           ms/op
ClientPb.getUser                        sample  232235   4.132 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.454           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.418           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.927           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.621           ms/op
ClientPb.listUser                       sample  197588   4.852 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.970           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.267           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.519           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.150           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.769           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
