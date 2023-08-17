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
# Warmup Iteration   1: 1.250 ops/ms
# Warmup Iteration   2: 2.915 ops/ms
# Warmup Iteration   3: 6.088 ops/ms
Iteration   1: 6.022 ops/ms
Iteration   2: 6.325 ops/ms
Iteration   3: 6.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.208 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (6.022, 6.208, 6.325), stdev = 0.163
  CI (99.9%): [3.231, 9.185] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.982 ops/ms
# Warmup Iteration   2: 5.571 ops/ms
# Warmup Iteration   3: 6.574 ops/ms
Iteration   1: 6.775 ops/ms
Iteration   2: 7.022 ops/ms
Iteration   3: 6.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.877 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (6.775, 6.877, 7.022), stdev = 0.129
  CI (99.9%): [4.530, 9.224] (assumes normal distribution)


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
# Warmup Iteration   1: 1.949 ops/ms
# Warmup Iteration   2: 5.722 ops/ms
# Warmup Iteration   3: 6.499 ops/ms
Iteration   1: 5.972 ops/ms
Iteration   2: 6.047 ops/ms
Iteration   3: 6.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.121 ±(99.9%) 3.592 ops/ms [Average]
  (min, avg, max) = (5.972, 6.121, 6.344), stdev = 0.197
  CI (99.9%): [2.529, 9.713] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.817 ops/ms
# Warmup Iteration   2: 4.624 ops/ms
# Warmup Iteration   3: 5.608 ops/ms
Iteration   1: 5.741 ops/ms
Iteration   2: 5.730 ops/ms
Iteration   3: 5.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.739 ±(99.9%) 0.150 ops/ms [Average]
  (min, avg, max) = (5.730, 5.739, 5.746), stdev = 0.008
  CI (99.9%): [5.589, 5.889] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.913 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.257 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.273 ±(99.9%) 0.019 ms/op
Iteration   1: 5.199 ±(99.9%) 0.009 ms/op
Iteration   2: 5.234 ±(99.9%) 0.011 ms/op
Iteration   3: 5.151 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.195 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (5.151, 5.195, 5.234), stdev = 0.042
  CI (99.9%): [4.433, 5.956] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 15.838 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.307 ±(99.9%) 0.008 ms/op
Iteration   1: 5.331 ±(99.9%) 0.010 ms/op
Iteration   2: 5.101 ±(99.9%) 0.013 ms/op
Iteration   3: 5.150 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.194 ±(99.9%) 2.215 ms/op [Average]
  (min, avg, max) = (5.101, 5.194, 5.331), stdev = 0.121
  CI (99.9%): [2.979, 7.408] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 18.090 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.079 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.360 ±(99.9%) 0.009 ms/op
Iteration   1: 5.425 ±(99.9%) 0.007 ms/op
Iteration   2: 5.241 ±(99.9%) 0.011 ms/op
Iteration   3: 5.344 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.337 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (5.241, 5.337, 5.425), stdev = 0.092
  CI (99.9%): [3.657, 7.017] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.317 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.235 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.330 ±(99.9%) 0.012 ms/op
Iteration   1: 6.437 ±(99.9%) 0.011 ms/op
Iteration   2: 6.403 ±(99.9%) 0.023 ms/op
Iteration   3: 6.176 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.339 ±(99.9%) 2.585 ms/op [Average]
  (min, avg, max) = (6.176, 6.339, 6.437), stdev = 0.142
  CI (99.9%): [3.754, 8.923] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 16.629 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 7.113 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.768 ±(99.9%) 0.024 ms/op
Iteration   1: 5.358 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.545 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  23.218 ms/op
                 createUser·p0.9999: 35.717 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   2: 5.382 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.701 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  29.314 ms/op
                 createUser·p0.9999: 32.358 ms/op
                 createUser·p1.00:   34.603 ms/op

Iteration   3: 5.401 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.594 ms/op
                 createUser·p0.99:   10.204 ms/op
                 createUser·p0.999:  27.649 ms/op
                 createUser·p0.9999: 37.880 ms/op
                 createUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178436
  mean =      5.380 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 83606 
    [ 5.000,  7.500) = 84995 
    [ 7.500, 10.000) = 7566 
    [10.000, 12.500) = 1278 
    [12.500, 15.000) = 512 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     27.445 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     37.880 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 15.200 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.570 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.018 ±(99.9%) 0.017 ms/op
Iteration   1: 4.825 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   6.799 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  15.134 ms/op
                 existUser·p0.9999: 27.484 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 5.104 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  25.467 ms/op
                 existUser·p0.9999: 30.302 ms/op
                 existUser·p1.00:   31.785 ms/op

Iteration   3: 4.744 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.547 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   8.999 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 31.441 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 196328
  mean =      4.886 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 140166 
    [ 5.000,  7.500) = 49283 
    [ 7.500, 10.000) = 5282 
    [10.000, 12.500) = 1076 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.898 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     18.470 ms/op
     p(99.9900) =     29.986 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 15.967 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.075 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.430 ±(99.9%) 0.020 ms/op
Iteration   1: 5.617 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   7.143 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   12.976 ms/op
                 getUser·p0.999:  23.741 ms/op
                 getUser·p0.9999: 33.227 ms/op
                 getUser·p1.00:   34.603 ms/op

Iteration   2: 5.286 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   10.551 ms/op
                 getUser·p0.999:  25.330 ms/op
                 getUser·p0.9999: 30.680 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   3: 5.405 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.843 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.766 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  28.926 ms/op
                 getUser·p0.9999: 32.699 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176500
  mean =      5.433 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 77808 
    [ 5.000,  7.500) = 88072 
    [ 7.500, 10.000) = 7206 
    [10.000, 12.500) = 2193 
    [12.500, 15.000) = 726 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     24.068 ms/op
     p(99.9900) =     32.485 ms/op
     p(99.9990) =     35.632 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 18.273 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 8.013 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.202 ±(99.9%) 0.025 ms/op
Iteration   1: 5.952 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  26.483 ms/op
                 listUser·p0.9999: 42.115 ms/op
                 listUser·p1.00:   42.795 ms/op

Iteration   2: 5.771 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.884 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  27.427 ms/op
                 listUser·p0.9999: 30.762 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   3: 6.258 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  23.852 ms/op
                 listUser·p0.9999: 27.060 ms/op
                 listUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160287
  mean =      5.987 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 24179 
    [ 5.000, 10.000) = 132320 
    [10.000, 15.000) = 3281 
    [15.000, 20.000) = 180 
    [20.000, 25.000) = 116 
    [25.000, 30.000) = 166 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     40.958 ms/op
     p(99.9990) =     42.637 ms/op
     p(99.9999) =     42.795 ms/op
    p(100.0000) =     42.795 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.208 ± 2.977  ops/ms
ClientPb.existUser                       thrpt       3   6.877 ± 2.347  ops/ms
ClientPb.getUser                         thrpt       3   6.121 ± 3.592  ops/ms
ClientPb.listUser                        thrpt       3   5.739 ± 0.150  ops/ms
ClientPb.createUser                       avgt       3   5.195 ± 0.761   ms/op
ClientPb.existUser                        avgt       3   5.194 ± 2.215   ms/op
ClientPb.getUser                          avgt       3   5.337 ± 1.680   ms/op
ClientPb.listUser                         avgt       3   6.339 ± 2.585   ms/op
ClientPb.createUser                     sample  178436   5.380 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.595           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.635           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.568           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.445           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.848           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.880           ms/op
ClientPb.existUser                      sample  196328   4.886 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.236           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.601           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.470           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.986           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.785           ms/op
ClientPb.getUser                        sample  176500   5.433 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.135           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.930           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.068           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.485           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  160287   5.987 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.367           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.919           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.958           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.795           ms/op
