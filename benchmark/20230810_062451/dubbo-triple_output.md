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
# Warmup Iteration   1: 1.210 ops/ms
# Warmup Iteration   2: 2.929 ops/ms
# Warmup Iteration   3: 5.788 ops/ms
Iteration   1: 5.671 ops/ms
Iteration   2: 6.143 ops/ms
Iteration   3: 6.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.003 ±(99.9%) 5.265 ops/ms [Average]
  (min, avg, max) = (5.671, 6.003, 6.194), stdev = 0.289
  CI (99.9%): [0.737, 11.268] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.878 ops/ms
# Warmup Iteration   2: 5.231 ops/ms
# Warmup Iteration   3: 6.104 ops/ms
Iteration   1: 6.261 ops/ms
Iteration   2: 6.287 ops/ms
Iteration   3: 6.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.269 ±(99.9%) 0.289 ops/ms [Average]
  (min, avg, max) = (6.258, 6.269, 6.287), stdev = 0.016
  CI (99.9%): [5.980, 6.558] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.882 ops/ms
# Warmup Iteration   2: 4.906 ops/ms
# Warmup Iteration   3: 5.776 ops/ms
Iteration   1: 5.945 ops/ms
Iteration   2: 6.035 ops/ms
Iteration   3: 5.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.975 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (5.945, 5.975, 6.035), stdev = 0.051
  CI (99.9%): [5.039, 6.911] (assumes normal distribution)


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
# Warmup Iteration   1: 1.701 ops/ms
# Warmup Iteration   2: 4.459 ops/ms
# Warmup Iteration   3: 5.066 ops/ms
Iteration   1: 5.056 ops/ms
Iteration   2: 5.513 ops/ms
Iteration   3: 5.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.286 ±(99.9%) 4.169 ops/ms [Average]
  (min, avg, max) = (5.056, 5.286, 5.513), stdev = 0.228
  CI (99.9%): [1.117, 9.454] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.377 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 6.283 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.564 ±(99.9%) 0.010 ms/op
Iteration   1: 5.386 ±(99.9%) 0.015 ms/op
Iteration   2: 5.309 ±(99.9%) 0.013 ms/op
Iteration   3: 5.265 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.320 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (5.265, 5.320, 5.386), stdev = 0.062
  CI (99.9%): [4.198, 6.443] (assumes normal distribution)


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
# Warmup Iteration   1: 15.227 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.202 ±(99.9%) 0.009 ms/op
Iteration   1: 5.084 ±(99.9%) 0.008 ms/op
Iteration   2: 4.936 ±(99.9%) 0.015 ms/op
Iteration   3: 4.913 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.978 ±(99.9%) 1.693 ms/op [Average]
  (min, avg, max) = (4.913, 4.978, 5.084), stdev = 0.093
  CI (99.9%): [3.284, 6.671] (assumes normal distribution)


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
# Warmup Iteration   1: 15.731 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.995 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.468 ±(99.9%) 0.009 ms/op
Iteration   1: 5.396 ±(99.9%) 0.010 ms/op
Iteration   2: 5.287 ±(99.9%) 0.017 ms/op
Iteration   3: 5.229 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.304 ±(99.9%) 1.541 ms/op [Average]
  (min, avg, max) = (5.229, 5.304, 5.396), stdev = 0.084
  CI (99.9%): [3.763, 6.845] (assumes normal distribution)


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
# Warmup Iteration   1: 17.988 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 7.188 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.368 ±(99.9%) 0.008 ms/op
Iteration   1: 5.993 ±(99.9%) 0.017 ms/op
Iteration   2: 5.907 ±(99.9%) 0.022 ms/op
Iteration   3: 6.201 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.033 ±(99.9%) 2.761 ms/op [Average]
  (min, avg, max) = (5.907, 6.033, 6.201), stdev = 0.151
  CI (99.9%): [3.272, 8.794] (assumes normal distribution)


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
# Warmup Iteration   1: 16.833 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.610 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.675 ±(99.9%) 0.027 ms/op
Iteration   1: 5.232 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.037 ms/op
                 createUser·p0.99:   10.074 ms/op
                 createUser·p0.999:  20.309 ms/op
                 createUser·p0.9999: 31.428 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   2: 5.444 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.913 ms/op
                 createUser·p0.99:   11.797 ms/op
                 createUser·p0.999:  26.387 ms/op
                 createUser·p0.9999: 30.179 ms/op
                 createUser·p1.00:   31.130 ms/op

Iteration   3: 5.332 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  25.360 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179897
  mean =      5.335 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 84972 
    [ 5.000,  7.500) = 85754 
    [ 7.500, 10.000) = 6932 
    [10.000, 12.500) = 1388 
    [12.500, 15.000) = 454 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.520 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     21.928 ms/op
     p(99.9900) =     30.213 ms/op
     p(99.9990) =     31.910 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 15.707 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.024 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.165 ±(99.9%) 0.017 ms/op
Iteration   1: 5.355 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.298 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.889 ms/op
                 existUser·p0.95:   8.036 ms/op
                 existUser·p0.99:   10.928 ms/op
                 existUser·p0.999:  21.499 ms/op
                 existUser·p0.9999: 33.424 ms/op
                 existUser·p1.00:   34.996 ms/op

Iteration   2: 5.178 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   9.994 ms/op
                 existUser·p0.999:  15.352 ms/op
                 existUser·p0.9999: 26.657 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 4.979 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   5.792 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   9.863 ms/op
                 existUser·p0.999:  23.661 ms/op
                 existUser·p0.9999: 33.180 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185638
  mean =      5.166 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 104934 
    [ 5.000,  7.500) = 71819 
    [ 7.500, 10.000) = 6794 
    [10.000, 12.500) = 1495 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     33.110 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 15.726 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 5.853 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.347 ±(99.9%) 0.018 ms/op
Iteration   1: 5.166 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.666 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   7.021 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  22.644 ms/op
                 getUser·p0.9999: 29.216 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   2: 5.245 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.081 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.283 ms/op
                 getUser·p0.95:   7.094 ms/op
                 getUser·p0.99:   10.437 ms/op
                 getUser·p0.999:  24.952 ms/op
                 getUser·p0.9999: 28.865 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 5.333 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.104 ms/op
                 getUser·p0.99:   10.043 ms/op
                 getUser·p0.999:  14.024 ms/op
                 getUser·p0.9999: 32.866 ms/op
                 getUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182961
  mean =      5.247 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 91368 
    [ 5.000,  7.500) = 84361 
    [ 7.500, 10.000) = 5210 
    [10.000, 12.500) = 1485 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     30.989 ms/op
     p(99.9990) =     33.140 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 18.996 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 7.215 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.128 ±(99.9%) 0.023 ms/op
Iteration   1: 6.183 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   11.451 ms/op
                 listUser·p0.999:  30.343 ms/op
                 listUser·p0.9999: 36.285 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   2: 6.118 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.707 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  27.669 ms/op
                 listUser·p0.9999: 34.406 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   3: 6.168 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.125 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.192 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  19.444 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155883
  mean =      6.156 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 9950 
    [ 5.000,  7.500) = 132678 
    [ 7.500, 10.000) = 9361 
    [10.000, 12.500) = 3057 
    [12.500, 15.000) = 441 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 49 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.564 ms/op
     p(50.0000) =      5.833 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     28.049 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.627 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.003 ± 5.265  ops/ms
ClientPb.existUser                       thrpt       3   6.269 ± 0.289  ops/ms
ClientPb.getUser                         thrpt       3   5.975 ± 0.936  ops/ms
ClientPb.listUser                        thrpt       3   5.286 ± 4.169  ops/ms
ClientPb.createUser                       avgt       3   5.320 ± 1.123   ms/op
ClientPb.existUser                        avgt       3   4.978 ± 1.693   ms/op
ClientPb.getUser                          avgt       3   5.304 ± 1.541   ms/op
ClientPb.listUser                         avgt       3   6.033 ± 2.761   ms/op
ClientPb.createUser                     sample  179897   5.335 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.457           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.520           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.502           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.928           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.213           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.145           ms/op
ClientPb.existUser                      sample  185638   5.166 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.422           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.110           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  182961   5.247 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.675           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.224           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.989           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  155883   6.156 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.564           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.403           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.049           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.406           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.700           ms/op
