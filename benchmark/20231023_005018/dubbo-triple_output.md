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
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 5.602 ops/ms
# Warmup Iteration   3: 8.784 ops/ms
Iteration   1: 9.723 ops/ms
Iteration   2: 9.792 ops/ms
Iteration   3: 9.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.763 ±(99.9%) 0.659 ops/ms [Average]
  (min, avg, max) = (9.723, 9.763, 9.792), stdev = 0.036
  CI (99.9%): [9.104, 10.422] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ops/ms
# Warmup Iteration   2: 8.945 ops/ms
# Warmup Iteration   3: 9.845 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 9.918 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.060 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (9.918, 10.060, 10.134), stdev = 0.123
  CI (99.9%): [7.808, 12.313] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.613 ops/ms
# Warmup Iteration   2: 8.445 ops/ms
# Warmup Iteration   3: 9.500 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 9.814 ops/ms
Iteration   3: 9.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.809 ±(99.9%) 0.887 ops/ms [Average]
  (min, avg, max) = (9.758, 9.809, 9.855), stdev = 0.049
  CI (99.9%): [8.922, 10.696] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.749 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.339 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.280 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (8.159, 8.280, 8.343), stdev = 0.105
  CI (99.9%): [6.360, 10.200] (assumes normal distribution)


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
# Warmup Iteration   1: 7.964 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.002 ms/op
Iteration   1: 3.279 ±(99.9%) 0.002 ms/op
Iteration   2: 3.229 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.230 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.181, 3.230, 3.279), stdev = 0.049
  CI (99.9%): [2.340, 4.119] (assumes normal distribution)


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
# Warmup Iteration   1: 7.452 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.002 ms/op
Iteration   1: 3.171 ±(99.9%) 0.003 ms/op
Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
Iteration   3: 3.205 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.172 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.140, 3.172, 3.205), stdev = 0.033
  CI (99.9%): [2.571, 3.773] (assumes normal distribution)


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
# Warmup Iteration   1: 8.931 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.002 ms/op
Iteration   1: 3.280 ±(99.9%) 0.003 ms/op
Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
Iteration   3: 3.339 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.287 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (3.242, 3.287, 3.339), stdev = 0.049
  CI (99.9%): [2.394, 4.180] (assumes normal distribution)


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
# Warmup Iteration   1: 9.708 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.006 ms/op
Iteration   1: 3.902 ±(99.9%) 0.006 ms/op
Iteration   2: 3.923 ±(99.9%) 0.004 ms/op
Iteration   3: 3.821 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.882 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (3.821, 3.882, 3.923), stdev = 0.054
  CI (99.9%): [2.902, 4.862] (assumes normal distribution)


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
# Warmup Iteration   1: 8.508 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.326 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.688 ms/op
                 createUser·p0.999:  17.727 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  16.830 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.155 ms/op
                 createUser·p0.9999: 21.701 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287927
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12383 
    [ 2.500,  5.000) = 270874 
    [ 5.000,  7.500) = 3530 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 162 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     17.926 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.876 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 8.593 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  9.621 ms/op
                 existUser·p0.9999: 21.858 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  15.196 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  12.644 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302475
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11268 
    [ 2.500,  5.000) = 286456 
    [ 5.000,  7.500) = 3818 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 181 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.234 ms/op
     p(99.9900) =     22.241 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 9.090 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.355 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 21.145 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 23.077 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  14.670 ms/op
                 getUser·p0.9999: 20.062 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292194
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12089 
    [ 2.500,  5.000) = 272930 
    [ 5.000,  7.500) = 6015 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.464 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 9.263 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
Iteration   1: 3.881 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.228 ms/op
                 listUser·p0.9999: 20.964 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 4.002 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.845 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  13.105 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245390
  mean =      3.909 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 236953 
    [ 5.000,  7.500) = 6971 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.763 ± 0.659  ops/ms
ClientPb.existUser                       thrpt       3  10.060 ± 2.252  ops/ms
ClientPb.getUser                         thrpt       3   9.809 ± 0.887  ops/ms
ClientPb.listUser                        thrpt       3   8.280 ± 1.920  ops/ms
ClientPb.createUser                       avgt       3   3.230 ± 0.889   ms/op
ClientPb.existUser                        avgt       3   3.172 ± 0.601   ms/op
ClientPb.getUser                          avgt       3   3.287 ± 0.893   ms/op
ClientPb.listUser                         avgt       3   3.882 ± 0.980   ms/op
ClientPb.createUser                     sample  287927   3.333 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.151           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.167           ms/op
ClientPb.existUser                      sample  302475   3.170 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.649           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.167           ms/op
ClientPb.getUser                        sample  292194   3.283 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.860           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.413           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.724           ms/op
ClientPb.listUser                       sample  245390   3.909 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.683           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.172           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.808           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.101           ms/op
