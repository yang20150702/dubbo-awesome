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
# Warmup Iteration   1: 2.505 ops/ms
# Warmup Iteration   2: 5.740 ops/ms
# Warmup Iteration   3: 9.398 ops/ms
Iteration   1: 9.961 ops/ms
Iteration   2: 9.836 ops/ms
Iteration   3: 9.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.808 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (9.629, 9.808, 9.961), stdev = 0.167
  CI (99.9%): [6.753, 12.864] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.613 ops/ms
# Warmup Iteration   2: 9.098 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 9.940 ops/ms
Iteration   2: 10.186 ops/ms
Iteration   3: 10.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.061 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (9.940, 10.061, 10.186), stdev = 0.123
  CI (99.9%): [7.816, 12.306] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 8.264 ops/ms
# Warmup Iteration   3: 9.598 ops/ms
Iteration   1: 9.428 ops/ms
Iteration   2: 9.952 ops/ms
Iteration   3: 9.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.684 ±(99.9%) 4.784 ops/ms [Average]
  (min, avg, max) = (9.428, 9.684, 9.952), stdev = 0.262
  CI (99.9%): [4.900, 14.468] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.115 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 8.578 ops/ms
Iteration   1: 8.690 ops/ms
Iteration   2: 8.423 ops/ms
Iteration   3: 8.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.565 ±(99.9%) 2.455 ops/ms [Average]
  (min, avg, max) = (8.423, 8.565, 8.690), stdev = 0.135
  CI (99.9%): [6.111, 11.020] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.301 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.005 ms/op
Iteration   1: 3.338 ±(99.9%) 0.004 ms/op
Iteration   2: 3.330 ±(99.9%) 0.005 ms/op
Iteration   3: 3.336 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.335 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (3.330, 3.335, 3.338), stdev = 0.004
  CI (99.9%): [3.262, 3.408] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.696 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.005 ms/op
Iteration   1: 3.268 ±(99.9%) 0.003 ms/op
Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
Iteration   3: 3.155 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.172 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (3.093, 3.172, 3.268), stdev = 0.089
  CI (99.9%): [1.549, 4.794] (assumes normal distribution)


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
# Warmup Iteration   1: 8.686 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.005 ms/op
Iteration   1: 3.218 ±(99.9%) 0.002 ms/op
Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
Iteration   3: 3.208 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.174 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.095, 3.174, 3.218), stdev = 0.068
  CI (99.9%): [1.926, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 8.160 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.007 ms/op
Iteration   1: 3.734 ±(99.9%) 0.007 ms/op
Iteration   2: 3.773 ±(99.9%) 0.007 ms/op
Iteration   3: 3.795 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.767 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.734, 3.767, 3.795), stdev = 0.031
  CI (99.9%): [3.207, 4.328] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.139 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.011 ms/op
Iteration   1: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.600 ms/op
                 createUser·p0.999:  12.773 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  19.118 ms/op
                 createUser·p0.9999: 23.457 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  15.372 ms/op
                 createUser·p0.9999: 22.155 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294716
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21125 
    [ 2.500,  5.000) = 266784 
    [ 5.000,  7.500) = 5382 
    [ 7.500, 10.000) = 897 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     22.332 ms/op
     p(99.9990) =     23.795 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.144 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 24.735 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  12.586 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.325 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  16.410 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296566
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22941 
    [ 2.500,  5.000) = 265992 
    [ 5.000,  7.500) = 6418 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     15.831 ms/op
     p(99.9900) =     25.232 ms/op
     p(99.9990) =     27.626 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 9.056 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.011 ms/op
Iteration   1: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  16.984 ms/op
                 getUser·p0.9999: 20.161 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.275 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  14.720 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  11.112 ms/op
                 getUser·p0.9999: 23.302 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289966
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10525 
    [ 2.500,  5.000) = 270146 
    [ 5.000,  7.500) = 7703 
    [ 7.500, 10.000) = 1206 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     14.470 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     23.534 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 9.529 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.013 ms/op
Iteration   1: 3.814 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.413 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 21.975 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   16.581 ms/op

Iteration   3: 3.722 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.290 ms/op
                 listUser·p0.999:  12.740 ms/op
                 listUser·p0.9999: 13.484 ms/op
                 listUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252263
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 242684 
    [ 5.000,  7.500) = 6893 
    [ 7.500, 10.000) = 1932 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     21.612 ms/op
     p(99.9990) =     22.379 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.808 ± 3.055  ops/ms
ClientPb.existUser                       thrpt       3  10.061 ± 2.245  ops/ms
ClientPb.getUser                         thrpt       3   9.684 ± 4.784  ops/ms
ClientPb.listUser                        thrpt       3   8.565 ± 2.455  ops/ms
ClientPb.createUser                       avgt       3   3.335 ± 0.073   ms/op
ClientPb.existUser                        avgt       3   3.172 ± 1.623   ms/op
ClientPb.getUser                          avgt       3   3.174 ± 1.248   ms/op
ClientPb.listUser                         avgt       3   3.767 ± 0.561   ms/op
ClientPb.createUser                     sample  294716   3.255 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.487           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.332           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  296566   3.236 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.831           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.232           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.722           ms/op
ClientPb.getUser                        sample  289966   3.309 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.470           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.020           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.593           ms/op
ClientPb.listUser                       sample  252263   3.805 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.612           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
