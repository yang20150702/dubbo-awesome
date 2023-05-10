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
# Warmup Iteration   1: 2.543 ops/ms
# Warmup Iteration   2: 6.257 ops/ms
# Warmup Iteration   3: 9.377 ops/ms
Iteration   1: 9.889 ops/ms
Iteration   2: 9.812 ops/ms
Iteration   3: 9.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.849 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (9.812, 9.849, 9.889), stdev = 0.038
  CI (99.9%): [9.147, 10.551] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 9.418 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 10.342 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.364 ±(99.9%) 0.452 ops/ms [Average]
  (min, avg, max) = (10.342, 10.364, 10.391), stdev = 0.025
  CI (99.9%): [9.911, 10.816] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ops/ms
# Warmup Iteration   2: 9.487 ops/ms
# Warmup Iteration   3: 9.634 ops/ms
Iteration   1: 9.984 ops/ms
Iteration   2: 9.761 ops/ms
Iteration   3: 10.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.964 ±(99.9%) 3.539 ops/ms [Average]
  (min, avg, max) = (9.761, 9.964, 10.147), stdev = 0.194
  CI (99.9%): [6.425, 13.503] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 7.598 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.658 ops/ms
Iteration   2: 8.739 ops/ms
Iteration   3: 8.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.684 ±(99.9%) 0.870 ops/ms [Average]
  (min, avg, max) = (8.654, 8.684, 8.739), stdev = 0.048
  CI (99.9%): [7.814, 9.553] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.581 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.008 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
Iteration   2: 3.336 ±(99.9%) 0.005 ms/op
Iteration   3: 3.249 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.283 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.249, 3.283, 3.336), stdev = 0.046
  CI (99.9%): [2.442, 4.125] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.684 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
Iteration   3: 3.101 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.043 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (2.997, 3.043, 3.101), stdev = 0.053
  CI (99.9%): [2.071, 4.014] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.002 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
Iteration   2: 3.219 ±(99.9%) 0.002 ms/op
Iteration   3: 3.147 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.170 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.145, 3.170, 3.219), stdev = 0.042
  CI (99.9%): [2.403, 3.938] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.125 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.005 ms/op
Iteration   1: 3.794 ±(99.9%) 0.008 ms/op
Iteration   2: 3.748 ±(99.9%) 0.009 ms/op
Iteration   3: 3.748 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.763 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.748, 3.763, 3.794), stdev = 0.027
  CI (99.9%): [3.277, 4.250] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.093 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.010 ms/op
Iteration   1: 3.207 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 29.069 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  12.206 ms/op
                 createUser·p0.9999: 25.006 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  16.991 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296679
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17443 
    [ 2.500,  5.000) = 273770 
    [ 5.000,  7.500) = 4701 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     18.185 ms/op
     p(99.9900) =     27.645 ms/op
     p(99.9990) =     29.626 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.951 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.008 ms/op
Iteration   1: 3.255 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  12.154 ms/op
                 existUser·p0.9999: 20.093 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 29.352 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303691
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27353 
    [ 2.500,  5.000) = 270584 
    [ 5.000,  7.500) = 4959 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     31.412 ms/op
     p(99.9990) =     34.142 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.755 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
Iteration   1: 3.340 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.480 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  16.550 ms/op
                 getUser·p0.9999: 24.073 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 20.503 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  11.915 ms/op
                 getUser·p0.9999: 23.094 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299666
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15118 
    [ 2.500,  5.000) = 277495 
    [ 5.000,  7.500) = 6280 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.675 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.932 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.011 ms/op
Iteration   1: 3.973 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.057 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 20.575 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   2: 3.793 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 16.742 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.774 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.306 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 17.860 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249728
  mean =      3.844 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 242833 
    [ 5.000,  7.500) = 4987 
    [ 7.500, 10.000) = 1189 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     18.548 ms/op
     p(99.9990) =     22.712 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.849 ± 0.702  ops/ms
ClientPb.existUser                       thrpt       3  10.364 ± 0.452  ops/ms
ClientPb.getUser                         thrpt       3   9.964 ± 3.539  ops/ms
ClientPb.listUser                        thrpt       3   8.684 ± 0.870  ops/ms
ClientPb.createUser                       avgt       3   3.283 ± 0.841   ms/op
ClientPb.existUser                        avgt       3   3.043 ± 0.971   ms/op
ClientPb.getUser                          avgt       3   3.170 ± 0.768   ms/op
ClientPb.listUser                         avgt       3   3.763 ± 0.487   ms/op
ClientPb.createUser                     sample  296679   3.235 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.932           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.185           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.645           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  303691   3.158 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  299666   3.205 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.480           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.101           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  249728   3.844 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.003           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.548           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.822           ms/op
