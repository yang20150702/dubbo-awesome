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
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 5.643 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 9.698 ops/ms
Iteration   3: 9.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.689 ±(99.9%) 3.166 ops/ms [Average]
  (min, avg, max) = (9.512, 9.689, 9.858), stdev = 0.174
  CI (99.9%): [6.524, 12.855] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 9.427 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.345 ops/ms
Iteration   3: 10.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.376 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (10.345, 10.376, 10.419), stdev = 0.039
  CI (99.9%): [9.669, 11.082] (assumes normal distribution)


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
# Warmup Iteration   1: 3.294 ops/ms
# Warmup Iteration   2: 8.783 ops/ms
# Warmup Iteration   3: 9.100 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 9.706 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.833 ±(99.9%) 3.444 ops/ms [Average]
  (min, avg, max) = (9.706, 9.833, 10.050), stdev = 0.189
  CI (99.9%): [6.390, 13.277] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ops/ms
# Warmup Iteration   2: 7.122 ops/ms
# Warmup Iteration   3: 8.058 ops/ms
Iteration   1: 8.488 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.282 ±(99.9%) 3.328 ops/ms [Average]
  (min, avg, max) = (8.141, 8.282, 8.488), stdev = 0.182
  CI (99.9%): [4.954, 11.610] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.008 ms/op
Iteration   1: 3.316 ±(99.9%) 0.009 ms/op
Iteration   2: 3.261 ±(99.9%) 0.006 ms/op
Iteration   3: 3.344 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.307 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.261, 3.307, 3.344), stdev = 0.043
  CI (99.9%): [2.530, 4.084] (assumes normal distribution)


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
# Warmup Iteration   1: 6.811 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.003 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.099 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.124 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.099, 3.124, 3.163), stdev = 0.035
  CI (99.9%): [2.489, 3.758] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.685 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.005 ms/op
Iteration   1: 3.308 ±(99.9%) 0.004 ms/op
Iteration   2: 3.224 ±(99.9%) 0.004 ms/op
Iteration   3: 3.240 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.258 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (3.224, 3.258, 3.308), stdev = 0.045
  CI (99.9%): [2.444, 4.071] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.304 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.003 ms/op
Iteration   1: 3.804 ±(99.9%) 0.006 ms/op
Iteration   2: 3.747 ±(99.9%) 0.011 ms/op
Iteration   3: 3.774 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.747, 3.775, 3.804), stdev = 0.029
  CI (99.9%): [3.252, 4.298] (assumes normal distribution)


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
# Warmup Iteration   1: 9.990 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.010 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  15.450 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  12.155 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 23.012 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297992
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15781 
    [ 2.500,  5.000) = 275621 
    [ 5.000,  7.500) = 5162 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     22.158 ms/op
     p(99.9990) =     23.759 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 7.037 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.250 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.079 ms/op
                 existUser·p0.9999: 26.384 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.200 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.217 ms/op
                 existUser·p0.999:  14.074 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  11.053 ms/op
                 existUser·p0.9999: 21.798 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295809
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24132 
    [ 2.500,  5.000) = 263842 
    [ 5.000,  7.500) = 6391 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     24.800 ms/op
     p(99.9990) =     26.871 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 8.447 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.012 ms/op
Iteration   1: 3.247 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  14.451 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  9.830 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.821 ms/op
                 getUser·p0.999:  10.447 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300089
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13742 
    [ 2.500,  5.000) = 279159 
    [ 5.000,  7.500) = 5628 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 163 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     13.408 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 8.790 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.013 ms/op
Iteration   1: 3.904 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 27.853 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 3.857 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.582 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 14.163 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   3: 3.768 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.567 ms/op
                 listUser·p0.9999: 13.941 ms/op
                 listUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249735
  mean =      3.842 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 240290 
    [ 5.000,  7.500) = 6702 
    [ 7.500, 10.000) = 1974 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     25.430 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.689 ± 3.166  ops/ms
ClientPb.existUser                       thrpt       3  10.376 ± 0.706  ops/ms
ClientPb.getUser                         thrpt       3   9.833 ± 3.444  ops/ms
ClientPb.listUser                        thrpt       3   8.282 ± 3.328  ops/ms
ClientPb.createUser                       avgt       3   3.307 ± 0.777   ms/op
ClientPb.existUser                        avgt       3   3.124 ± 0.634   ms/op
ClientPb.getUser                          avgt       3   3.258 ± 0.814   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 0.523   ms/op
ClientPb.createUser                     sample  297992   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.079           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.418           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.158           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  295809   3.240 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.042           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.029           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.800           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  300089   3.197 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.408           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.739           ms/op
ClientPb.listUser                       sample  249735   3.842 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.435           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.430           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.836           ms/op
