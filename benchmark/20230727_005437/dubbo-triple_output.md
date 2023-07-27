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
# Warmup Iteration   1: 1.995 ops/ms
# Warmup Iteration   2: 4.626 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.750 ops/ms
Iteration   2: 9.147 ops/ms
Iteration   3: 9.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.057 ±(99.9%) 4.995 ops/ms [Average]
  (min, avg, max) = (8.750, 9.057, 9.275), stdev = 0.274
  CI (99.9%): [4.062, 14.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.938 ops/ms
# Warmup Iteration   2: 8.762 ops/ms
# Warmup Iteration   3: 9.318 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 9.912 ops/ms
Iteration   3: 9.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.688 ±(99.9%) 3.599 ops/ms [Average]
  (min, avg, max) = (9.540, 9.688, 9.912), stdev = 0.197
  CI (99.9%): [6.089, 13.287] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.866 ops/ms
# Warmup Iteration   2: 8.353 ops/ms
# Warmup Iteration   3: 9.194 ops/ms
Iteration   1: 8.919 ops/ms
Iteration   2: 9.455 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.264 ±(99.9%) 5.470 ops/ms [Average]
  (min, avg, max) = (8.919, 9.264, 9.455), stdev = 0.300
  CI (99.9%): [3.795, 14.734] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.782 ops/ms
# Warmup Iteration   2: 6.998 ops/ms
# Warmup Iteration   3: 7.843 ops/ms
Iteration   1: 7.922 ops/ms
Iteration   2: 7.945 ops/ms
Iteration   3: 8.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.980 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (7.922, 7.980, 8.074), stdev = 0.082
  CI (99.9%): [6.491, 9.470] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.920 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.004 ms/op
Iteration   1: 3.461 ±(99.9%) 0.005 ms/op
Iteration   2: 3.530 ±(99.9%) 0.006 ms/op
Iteration   3: 3.499 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.496 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.461, 3.496, 3.530), stdev = 0.035
  CI (99.9%): [2.864, 4.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.403 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.004 ms/op
Iteration   1: 3.266 ±(99.9%) 0.005 ms/op
Iteration   2: 3.296 ±(99.9%) 0.010 ms/op
Iteration   3: 3.460 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.341 ±(99.9%) 1.902 ms/op [Average]
  (min, avg, max) = (3.266, 3.341, 3.460), stdev = 0.104
  CI (99.9%): [1.439, 5.243] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 11.075 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.008 ms/op
Iteration   1: 3.530 ±(99.9%) 0.003 ms/op
Iteration   2: 3.492 ±(99.9%) 0.003 ms/op
Iteration   3: 3.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.475 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (3.403, 3.475, 3.530), stdev = 0.065
  CI (99.9%): [2.284, 4.665] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.983 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.010 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
Iteration   3: 3.963 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.974 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.963, 3.974, 3.989), stdev = 0.014
  CI (99.9%): [3.727, 4.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.194 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.015 ms/op
Iteration   1: 3.506 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.774 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.535 ms/op
                 createUser·p0.999:  20.218 ms/op
                 createUser·p0.9999: 23.360 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.583 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.650 ms/op
                 createUser·p0.9999: 26.086 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  20.611 ms/op
                 createUser·p0.9999: 32.131 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272777
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7071 
    [ 2.500,  5.000) = 256341 
    [ 5.000,  7.500) = 7643 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     20.487 ms/op
     p(99.9900) =     30.398 ms/op
     p(99.9990) =     32.789 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 7.862 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
Iteration   1: 3.331 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  17.477 ms/op
                 existUser·p0.9999: 23.664 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.488 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.334 ms/op
                 existUser·p0.999:  19.678 ms/op
                 existUser·p0.9999: 22.539 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.403 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  11.930 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281654
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17424 
    [ 2.500,  5.000) = 253667 
    [ 5.000,  7.500) = 8687 
    [ 7.500, 10.000) = 1423 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     27.320 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 9.489 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  22.161 ms/op
                 getUser·p0.9999: 24.498 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.384 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 26.444 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.606 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  13.511 ms/op
                 getUser·p0.9999: 27.481 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276863
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4155 
    [ 2.500,  5.000) = 262959 
    [ 5.000,  7.500) = 8338 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.855 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.069 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.721 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.014 ms/op
Iteration   1: 4.162 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.020 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  23.046 ms/op
                 listUser·p0.9999: 26.651 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.143 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  16.102 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232781
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 223214 
    [ 5.000,  7.500) = 6713 
    [ 7.500, 10.000) = 1715 
    [10.000, 12.500) = 573 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     24.960 ms/op
     p(99.9990) =     27.100 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.057 ± 4.995  ops/ms
ClientPb.existUser                       thrpt       3   9.688 ± 3.599  ops/ms
ClientPb.getUser                         thrpt       3   9.264 ± 5.470  ops/ms
ClientPb.listUser                        thrpt       3   7.980 ± 1.489  ops/ms
ClientPb.createUser                       avgt       3   3.496 ± 0.632   ms/op
ClientPb.existUser                        avgt       3   3.341 ± 1.902   ms/op
ClientPb.getUser                          avgt       3   3.475 ± 1.190   ms/op
ClientPb.listUser                         avgt       3   3.974 ± 0.247   ms/op
ClientPb.createUser                     sample  272777   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.487           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  281654   3.406 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.053           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279           ms/op
ClientPb.getUser                        sample  276863   3.466 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.452           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.628           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.509           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  232781   4.124 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.354           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.954           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.165           ms/op
