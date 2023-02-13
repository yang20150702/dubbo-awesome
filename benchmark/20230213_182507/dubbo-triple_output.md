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
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 6.188 ops/ms
# Warmup Iteration   3: 9.301 ops/ms
Iteration   1: 9.753 ops/ms
Iteration   2: 9.834 ops/ms
Iteration   3: 10.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.971 ±(99.9%) 5.648 ops/ms [Average]
  (min, avg, max) = (9.753, 9.971, 10.325), stdev = 0.310
  CI (99.9%): [4.323, 15.619] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ops/ms
# Warmup Iteration   2: 9.781 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.264 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.438 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (10.264, 10.438, 10.598), stdev = 0.167
  CI (99.9%): [7.383, 13.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 9.155 ops/ms
# Warmup Iteration   3: 9.885 ops/ms
Iteration   1: 9.670 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.909 ±(99.9%) 5.081 ops/ms [Average]
  (min, avg, max) = (9.670, 9.909, 10.215), stdev = 0.279
  CI (99.9%): [4.828, 14.990] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.946 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.532 ops/ms
Iteration   2: 8.747 ops/ms
Iteration   3: 8.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.657 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (8.532, 8.657, 8.747), stdev = 0.112
  CI (99.9%): [6.621, 10.694] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.796 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.003 ms/op
Iteration   1: 3.304 ±(99.9%) 0.005 ms/op
Iteration   2: 3.335 ±(99.9%) 0.003 ms/op
Iteration   3: 3.161 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.266 ±(99.9%) 1.695 ms/op [Average]
  (min, avg, max) = (3.161, 3.266, 3.335), stdev = 0.093
  CI (99.9%): [1.572, 4.961] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.361 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
Iteration   3: 3.035 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.023 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (2.968, 3.023, 3.066), stdev = 0.050
  CI (99.9%): [2.108, 3.938] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.138 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.004 ms/op
Iteration   1: 3.024 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.004 ms/op
Iteration   3: 3.206 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.087 ±(99.9%) 1.872 ms/op [Average]
  (min, avg, max) = (3.024, 3.087, 3.206), stdev = 0.103
  CI (99.9%): [1.216, 4.959] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.727 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.007 ms/op
Iteration   1: 3.774 ±(99.9%) 0.007 ms/op
Iteration   2: 3.676 ±(99.9%) 0.009 ms/op
Iteration   3: 3.666 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.666, 3.705, 3.774), stdev = 0.059
  CI (99.9%): [2.624, 4.787] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.009 ms/op
Iteration   1: 3.128 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  12.755 ms/op
                 createUser·p0.9999: 27.419 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  9.732 ms/op
                 createUser·p0.9999: 25.551 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  10.681 ms/op
                 createUser·p0.9999: 18.835 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304570
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28679 
    [ 2.500,  5.000) = 271698 
    [ 5.000,  7.500) = 3379 
    [ 7.500, 10.000) = 457 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     10.998 ms/op
     p(99.9900) =     25.830 ms/op
     p(99.9990) =     28.012 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  8.466 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.289 ms/op
                 existUser·p0.999:  9.194 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309828
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37733 
    [ 2.500,  5.000) = 267622 
    [ 5.000,  7.500) = 3944 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =      9.735 ms/op
     p(99.9900) =     21.431 ms/op
     p(99.9990) =     22.535 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.451 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.009 ms/op
Iteration   1: 3.287 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.163 ms/op
                 getUser·p0.999:  16.205 ms/op
                 getUser·p0.9999: 20.030 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  9.235 ms/op
                 getUser·p0.9999: 28.464 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 18.050 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302046
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17715 
    [ 2.500,  5.000) = 276707 
    [ 5.000,  7.500) = 6784 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     13.642 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     28.995 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.199 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 3.744 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.368 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  11.944 ms/op
                 listUser·p0.9999: 13.730 ms/op
                 listUser·p1.00:   13.746 ms/op

Iteration   3: 3.640 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.125 ms/op
                 listUser·p0.99:   6.629 ms/op
                 listUser·p0.999:  11.758 ms/op
                 listUser·p0.9999: 15.415 ms/op
                 listUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259010
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 251505 
    [ 5.000,  7.500) = 5609 
    [ 7.500, 10.000) = 1051 
    [10.000, 12.500) = 467 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     20.696 ms/op
     p(99.9990) =     21.405 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.971 ± 5.648  ops/ms
ClientPb.existUser                       thrpt       3  10.438 ± 3.055  ops/ms
ClientPb.getUser                         thrpt       3   9.909 ± 5.081  ops/ms
ClientPb.listUser                        thrpt       3   8.657 ± 2.036  ops/ms
ClientPb.createUser                       avgt       3   3.266 ± 1.695   ms/op
ClientPb.existUser                        avgt       3   3.023 ± 0.915   ms/op
ClientPb.getUser                          avgt       3   3.087 ± 1.872   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 1.082   ms/op
ClientPb.createUser                     sample  304570   3.150 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.998           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.830           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.458           ms/op
ClientPb.existUser                      sample  309828   3.097 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.735           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.431           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.200           ms/op
ClientPb.getUser                        sample  302046   3.177 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.931           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.985           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.393           ms/op
ClientPb.listUser                       sample  259010   3.709 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.368           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.993           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.696           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.463           ms/op
