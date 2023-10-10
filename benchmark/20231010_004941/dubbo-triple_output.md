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
# Warmup Iteration   1: 2.304 ops/ms
# Warmup Iteration   2: 5.502 ops/ms
# Warmup Iteration   3: 9.241 ops/ms
Iteration   1: 9.685 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.605 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (9.486, 9.605, 9.685), stdev = 0.105
  CI (99.9%): [7.688, 11.522] (assumes normal distribution)


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
# Warmup Iteration   1: 3.435 ops/ms
# Warmup Iteration   2: 9.076 ops/ms
# Warmup Iteration   3: 10.048 ops/ms
Iteration   1: 10.371 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.276 ±(99.9%) 4.112 ops/ms [Average]
  (min, avg, max) = (10.019, 10.276, 10.439), stdev = 0.225
  CI (99.9%): [6.164, 14.389] (assumes normal distribution)


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
# Warmup Iteration   1: 3.368 ops/ms
# Warmup Iteration   2: 9.323 ops/ms
# Warmup Iteration   3: 9.507 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 9.907 ops/ms
Iteration   3: 9.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.705 ±(99.9%) 5.482 ops/ms [Average]
  (min, avg, max) = (9.360, 9.705, 9.907), stdev = 0.300
  CI (99.9%): [4.223, 15.187] (assumes normal distribution)


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
# Warmup Iteration   1: 2.828 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 8.063 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.281 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (8.245, 8.281, 8.352), stdev = 0.061
  CI (99.9%): [7.160, 9.403] (assumes normal distribution)


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
# Warmup Iteration   1: 9.528 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.004 ms/op
Iteration   1: 3.233 ±(99.9%) 0.004 ms/op
Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
Iteration   3: 3.353 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.272 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.230, 3.272, 3.353), stdev = 0.070
  CI (99.9%): [1.997, 4.547] (assumes normal distribution)


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
# Warmup Iteration   1: 8.121 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.003 ms/op
Iteration   1: 3.200 ±(99.9%) 0.003 ms/op
Iteration   2: 3.264 ±(99.9%) 0.002 ms/op
Iteration   3: 3.153 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.206 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.153, 3.206, 3.264), stdev = 0.055
  CI (99.9%): [2.194, 4.217] (assumes normal distribution)


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
# Warmup Iteration   1: 7.439 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.003 ms/op
Iteration   1: 3.310 ±(99.9%) 0.003 ms/op
Iteration   2: 3.290 ±(99.9%) 0.007 ms/op
Iteration   3: 3.245 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.282 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.245, 3.282, 3.310), stdev = 0.033
  CI (99.9%): [2.676, 3.888] (assumes normal distribution)


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
# Warmup Iteration   1: 9.700 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.004 ms/op
Iteration   1: 3.966 ±(99.9%) 0.004 ms/op
Iteration   2: 3.889 ±(99.9%) 0.005 ms/op
Iteration   3: 3.888 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.914 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.888, 3.914, 3.966), stdev = 0.045
  CI (99.9%): [3.096, 4.733] (assumes normal distribution)


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
# Warmup Iteration   1: 9.187 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.010 ms/op
Iteration   1: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.663 ms/op
                 createUser·p0.9999: 22.548 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 22.692 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.295 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  20.345 ms/op
                 createUser·p0.9999: 23.340 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294006
  mean =      3.265 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18876 
    [ 2.500,  5.000) = 269169 
    [ 5.000,  7.500) = 4685 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 192 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     29.108 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 8.952 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.010 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   6.338 ms/op
                 existUser·p0.999:  13.070 ms/op
                 existUser·p0.9999: 21.264 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  13.085 ms/op
                 existUser·p0.9999: 21.969 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   6.598 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 20.200 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297152
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14898 
    [ 2.500,  5.000) = 274426 
    [ 5.000,  7.500) = 6784 
    [ 7.500, 10.000) = 421 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.250 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 8.266 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.011 ms/op
Iteration   1: 3.401 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  18.805 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  16.844 ms/op
                 getUser·p0.9999: 21.226 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  16.627 ms/op
                 getUser·p0.9999: 23.352 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290323
  mean =      3.308 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7929 
    [ 2.500,  5.000) = 272776 
    [ 5.000,  7.500) = 8219 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     18.241 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     26.534 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 8.621 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.011 ms/op
Iteration   1: 3.917 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  14.260 ms/op
                 listUser·p0.9999: 44.642 ms/op
                 listUser·p1.00:   55.837 ms/op

Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 18.531 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.858 ms/op
                 listUser·p0.999:  15.924 ms/op
                 listUser·p0.9999: 19.408 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248631
  mean =      3.858 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 239614 
    [ 5.000, 10.000) = 8120 
    [10.000, 15.000) = 640 
    [15.000, 20.000) = 202 
    [20.000, 25.000) = 22 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 25 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.747 ms/op
     p(99.9000) =     15.210 ms/op
     p(99.9900) =     41.681 ms/op
     p(99.9990) =     46.433 ms/op
     p(99.9999) =     55.837 ms/op
    p(100.0000) =     55.837 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.605 ± 1.917  ops/ms
ClientPb.existUser                       thrpt       3  10.276 ± 4.112  ops/ms
ClientPb.getUser                         thrpt       3   9.705 ± 5.482  ops/ms
ClientPb.listUser                        thrpt       3   8.281 ± 1.121  ops/ms
ClientPb.createUser                       avgt       3   3.272 ± 1.275   ms/op
ClientPb.existUser                        avgt       3   3.206 ± 1.011   ms/op
ClientPb.getUser                          avgt       3   3.282 ± 0.606   ms/op
ClientPb.listUser                         avgt       3   3.914 ± 0.819   ms/op
ClientPb.createUser                     sample  294006   3.265 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.030           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.839           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  297152   3.229 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.018           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.561           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.315           ms/op
ClientPb.getUser                        sample  290323   3.308 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.725           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  248631   3.858 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.210           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.681           ms/op
ClientPb.listUser:listUser·p1.00        sample          55.837           ms/op
