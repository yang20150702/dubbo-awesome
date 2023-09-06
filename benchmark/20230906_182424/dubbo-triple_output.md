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
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 5.332 ops/ms
# Warmup Iteration   3: 8.875 ops/ms
Iteration   1: 9.216 ops/ms
Iteration   2: 9.642 ops/ms
Iteration   3: 9.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.470 ±(99.9%) 4.102 ops/ms [Average]
  (min, avg, max) = (9.216, 9.470, 9.642), stdev = 0.225
  CI (99.9%): [5.368, 13.572] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.055 ops/ms
# Warmup Iteration   2: 8.195 ops/ms
# Warmup Iteration   3: 9.625 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.103 ops/ms
Iteration   3: 9.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.040 ±(99.9%) 3.259 ops/ms [Average]
  (min, avg, max) = (9.838, 10.040, 10.179), stdev = 0.179
  CI (99.9%): [6.781, 13.299] (assumes normal distribution)


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
# Warmup Iteration   1: 2.968 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 8.871 ops/ms
Iteration   1: 9.524 ops/ms
Iteration   2: 9.727 ops/ms
Iteration   3: 9.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.652 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (9.524, 9.652, 9.727), stdev = 0.112
  CI (99.9%): [7.614, 11.690] (assumes normal distribution)


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
# Warmup Iteration   1: 2.871 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 8.214 ops/ms
Iteration   1: 8.147 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.274 ±(99.9%) 3.833 ops/ms [Average]
  (min, avg, max) = (8.147, 8.274, 8.516), stdev = 0.210
  CI (99.9%): [4.441, 12.107] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.215 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
Iteration   1: 3.285 ±(99.9%) 0.004 ms/op
Iteration   2: 3.228 ±(99.9%) 0.005 ms/op
Iteration   3: 3.254 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.256 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.228, 3.256, 3.285), stdev = 0.029
  CI (99.9%): [2.732, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 8.078 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.002 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
Iteration   3: 3.295 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.218 ±(99.9%) 1.231 ms/op [Average]
  (min, avg, max) = (3.171, 3.218, 3.295), stdev = 0.067
  CI (99.9%): [1.987, 4.448] (assumes normal distribution)


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
# Warmup Iteration   1: 9.145 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.005 ms/op
Iteration   1: 3.257 ±(99.9%) 0.003 ms/op
Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
Iteration   3: 3.245 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.214, 3.239, 3.257), stdev = 0.022
  CI (99.9%): [2.829, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 9.051 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.005 ms/op
Iteration   1: 4.073 ±(99.9%) 0.006 ms/op
Iteration   2: 3.967 ±(99.9%) 0.007 ms/op
Iteration   3: 3.872 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.971 ±(99.9%) 1.830 ms/op [Average]
  (min, avg, max) = (3.872, 3.971, 4.073), stdev = 0.100
  CI (99.9%): [2.141, 5.801] (assumes normal distribution)


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
# Warmup Iteration   1: 9.180 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.010 ms/op
Iteration   1: 3.360 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  20.952 ms/op
                 createUser·p0.9999: 23.999 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.318 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  20.168 ms/op
                 createUser·p0.9999: 30.048 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   3: 3.341 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  21.982 ms/op
                 createUser·p0.9999: 26.785 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287556
  mean =      3.339 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11702 
    [ 2.500,  5.000) = 268845 
    [ 5.000,  7.500) = 5853 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     20.891 ms/op
     p(99.9900) =     28.385 ms/op
     p(99.9990) =     31.228 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.194 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
Iteration   1: 3.302 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  18.045 ms/op
                 existUser·p0.9999: 24.761 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  11.848 ms/op
                 existUser·p0.9999: 26.495 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 27.957 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291909
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14521 
    [ 2.500,  5.000) = 269980 
    [ 5.000,  7.500) = 6089 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.781 ms/op
     p(99.9900) =     26.824 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 10.281 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.012 ms/op
Iteration   1: 3.266 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  19.628 ms/op
                 getUser·p0.9999: 29.400 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  10.441 ms/op
                 getUser·p0.9999: 24.944 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  15.961 ms/op
                 getUser·p0.9999: 26.634 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291766
  mean =      3.289 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8585 
    [ 2.500,  5.000) = 275459 
    [ 5.000,  7.500) = 6094 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     17.824 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     29.658 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 9.738 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.013 ms/op
Iteration   1: 3.935 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.253 ms/op
                 listUser·p0.999:  22.444 ms/op
                 listUser·p0.9999: 29.188 ms/op
                 listUser·p1.00:   30.704 ms/op

Iteration   2: 4.008 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.324 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.788 ms/op
                 listUser·p0.999:  15.727 ms/op
                 listUser·p0.9999: 18.708 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244069
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 233054 
    [ 5.000,  7.500) = 7765 
    [ 7.500, 10.000) = 1692 
    [10.000, 12.500) = 764 
    [12.500, 15.000) = 395 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.932 ms/op
     p(99.9000) =     16.055 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     29.823 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.470 ± 4.102  ops/ms
ClientPb.existUser                       thrpt       3  10.040 ± 3.259  ops/ms
ClientPb.getUser                         thrpt       3   9.652 ± 2.038  ops/ms
ClientPb.listUser                        thrpt       3   8.274 ± 3.833  ops/ms
ClientPb.createUser                       avgt       3   3.256 ± 0.523   ms/op
ClientPb.existUser                        avgt       3   3.218 ± 1.231   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 0.410   ms/op
ClientPb.listUser                         avgt       3   3.971 ± 1.830   ms/op
ClientPb.createUser                     sample  287556   3.339 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.891           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.385           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.785           ms/op
ClientPb.existUser                      sample  291909   3.288 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.781           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.824           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.229           ms/op
ClientPb.getUser                        sample  291766   3.289 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.317           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.824           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  244069   3.929 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.640           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.932           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.055           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.591           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.704           ms/op
