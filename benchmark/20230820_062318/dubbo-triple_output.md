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
# Warmup Iteration   1: 1.416 ops/ms
# Warmup Iteration   2: 2.981 ops/ms
# Warmup Iteration   3: 6.438 ops/ms
Iteration   1: 6.376 ops/ms
Iteration   2: 7.278 ops/ms
Iteration   3: 7.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.965 ±(99.9%) 9.323 ops/ms [Average]
  (min, avg, max) = (6.376, 6.965, 7.278), stdev = 0.511
  CI (99.9%): [≈ 0, 16.289] (assumes normal distribution)


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
# Warmup Iteration   1: 1.948 ops/ms
# Warmup Iteration   2: 4.796 ops/ms
# Warmup Iteration   3: 6.865 ops/ms
Iteration   1: 7.461 ops/ms
Iteration   2: 7.617 ops/ms
Iteration   3: 7.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.580 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (7.461, 7.580, 7.661), stdev = 0.105
  CI (99.9%): [5.660, 9.499] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.519 ops/ms
# Warmup Iteration   2: 4.917 ops/ms
# Warmup Iteration   3: 7.242 ops/ms
Iteration   1: 7.631 ops/ms
Iteration   2: 7.838 ops/ms
Iteration   3: 7.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.737 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (7.631, 7.737, 7.838), stdev = 0.104
  CI (99.9%): [5.841, 9.634] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.804 ops/ms
# Warmup Iteration   2: 5.142 ops/ms
# Warmup Iteration   3: 6.517 ops/ms
Iteration   1: 6.489 ops/ms
Iteration   2: 6.330 ops/ms
Iteration   3: 6.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.306 ±(99.9%) 3.585 ops/ms [Average]
  (min, avg, max) = (6.098, 6.306, 6.489), stdev = 0.196
  CI (99.9%): [2.721, 9.890] (assumes normal distribution)


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
# Warmup Iteration   1: 13.539 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.006 ms/op
Iteration   1: 4.130 ±(99.9%) 0.013 ms/op
Iteration   2: 4.402 ±(99.9%) 0.010 ms/op
Iteration   3: 4.479 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.337 ±(99.9%) 3.340 ms/op [Average]
  (min, avg, max) = (4.130, 4.337, 4.479), stdev = 0.183
  CI (99.9%): [0.997, 7.677] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.522 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.750 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.006 ms/op
Iteration   1: 4.101 ±(99.9%) 0.008 ms/op
Iteration   2: 3.885 ±(99.9%) 0.005 ms/op
Iteration   3: 4.070 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.019 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.885, 4.019, 4.101), stdev = 0.117
  CI (99.9%): [1.889, 6.148] (assumes normal distribution)


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
# Warmup Iteration   1: 14.441 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.006 ms/op
Iteration   1: 4.096 ±(99.9%) 0.005 ms/op
Iteration   2: 4.018 ±(99.9%) 0.010 ms/op
Iteration   3: 3.976 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.030 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.976, 4.030, 4.096), stdev = 0.061
  CI (99.9%): [2.919, 5.142] (assumes normal distribution)


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
# Warmup Iteration   1: 15.902 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.834 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.068 ±(99.9%) 0.010 ms/op
Iteration   1: 4.774 ±(99.9%) 0.009 ms/op
Iteration   2: 4.806 ±(99.9%) 0.010 ms/op
Iteration   3: 4.749 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.776 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (4.749, 4.776, 4.806), stdev = 0.029
  CI (99.9%): [4.249, 5.303] (assumes normal distribution)


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
# Warmup Iteration   1: 12.864 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.022 ms/op
Iteration   1: 4.443 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   6.734 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  24.741 ms/op
                 createUser·p0.9999: 27.768 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   2: 4.464 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   6.636 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 30.436 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 4.282 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.028 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   9.486 ms/op
                 createUser·p0.999:  28.736 ms/op
                 createUser·p0.9999: 38.601 ms/op
                 createUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 218254
  mean =      4.395 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 265 
    [ 2.500,  5.000) = 188362 
    [ 5.000,  7.500) = 23933 
    [ 7.500, 10.000) = 3619 
    [10.000, 12.500) = 1314 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     25.223 ms/op
     p(99.9900) =     38.022 ms/op
     p(99.9990) =     38.982 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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
# Warmup Iteration   1: 13.052 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 4.801 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
Iteration   1: 3.923 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  25.723 ms/op
                 existUser·p0.9999: 30.628 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   2: 3.885 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 29.451 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 4.166 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   8.782 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 34.865 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240591
  mean =      3.988 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 240 
    [ 2.500,  5.000) = 226144 
    [ 5.000,  7.500) = 10935 
    [ 7.500, 10.000) = 2176 
    [10.000, 12.500) = 743 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     14.645 ms/op
     p(99.9900) =     32.577 ms/op
     p(99.9990) =     35.244 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 15.778 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.259 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.018 ms/op
Iteration   1: 4.003 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   7.947 ms/op
                 getUser·p0.999:  23.531 ms/op
                 getUser·p0.9999: 25.921 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   2: 4.016 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  14.816 ms/op
                 getUser·p0.9999: 36.243 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   3: 4.341 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   5.266 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   9.273 ms/op
                 getUser·p0.999:  27.113 ms/op
                 getUser·p0.9999: 29.585 ms/op
                 getUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233377
  mean =      4.114 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 217223 
    [ 5.000,  7.500) = 11590 
    [ 7.500, 10.000) = 3513 
    [10.000, 12.500) = 664 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     33.991 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 14.586 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 6.309 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.023 ms/op
Iteration   1: 4.898 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  25.546 ms/op
                 listUser·p0.9999: 27.785 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 5.041 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  21.352 ms/op
                 listUser·p0.9999: 27.350 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 5.006 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   9.394 ms/op
                 listUser·p0.999:  17.357 ms/op
                 listUser·p0.9999: 20.467 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192663
  mean =      4.981 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 137240 
    [ 5.000,  7.500) = 48664 
    [ 7.500, 10.000) = 4998 
    [10.000, 12.500) = 1138 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 96 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     28.558 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.965 ± 9.323  ops/ms
ClientPb.existUser                       thrpt       3   7.580 ± 1.920  ops/ms
ClientPb.getUser                         thrpt       3   7.737 ± 1.896  ops/ms
ClientPb.listUser                        thrpt       3   6.306 ± 3.585  ops/ms
ClientPb.createUser                       avgt       3   4.337 ± 3.340   ms/op
ClientPb.existUser                        avgt       3   4.019 ± 2.129   ms/op
ClientPb.getUser                          avgt       3   4.030 ± 1.112   ms/op
ClientPb.listUser                         avgt       3   4.776 ± 0.527   ms/op
ClientPb.createUser                     sample  218254   4.395 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.863           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.223           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.022           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.994           ms/op
ClientPb.existUser                      sample  240591   3.988 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.004           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.645           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.577           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  233377   4.114 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.667           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.991           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  192663   4.981 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.430           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
