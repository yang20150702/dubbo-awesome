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
# Warmup Iteration   1: 1.076 ops/ms
# Warmup Iteration   2: 2.383 ops/ms
# Warmup Iteration   3: 5.306 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.596 ops/ms
Iteration   3: 5.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.712 ±(99.9%) 3.518 ops/ms [Average]
  (min, avg, max) = (5.596, 5.712, 5.934), stdev = 0.193
  CI (99.9%): [2.194, 9.230] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.957 ops/ms
# Warmup Iteration   3: 5.977 ops/ms
Iteration   1: 6.195 ops/ms
Iteration   2: 6.243 ops/ms
Iteration   3: 6.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.251 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (6.195, 6.251, 6.315), stdev = 0.060
  CI (99.9%): [5.152, 7.350] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.759 ops/ms
# Warmup Iteration   2: 4.923 ops/ms
# Warmup Iteration   3: 5.609 ops/ms
Iteration   1: 5.443 ops/ms
Iteration   2: 5.634 ops/ms
Iteration   3: 5.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.615 ±(99.9%) 2.991 ops/ms [Average]
  (min, avg, max) = (5.443, 5.615, 5.769), stdev = 0.164
  CI (99.9%): [2.625, 8.606] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.426 ops/ms
# Warmup Iteration   2: 3.873 ops/ms
# Warmup Iteration   3: 4.740 ops/ms
Iteration   1: 4.787 ops/ms
Iteration   2: 4.950 ops/ms
Iteration   3: 4.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.864 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (4.787, 4.864, 4.950), stdev = 0.082
  CI (99.9%): [3.367, 6.360] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.681 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.816 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.008 ±(99.9%) 0.009 ms/op
Iteration   1: 5.594 ±(99.9%) 0.012 ms/op
Iteration   2: 5.412 ±(99.9%) 0.015 ms/op
Iteration   3: 5.413 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.473 ±(99.9%) 1.909 ms/op [Average]
  (min, avg, max) = (5.412, 5.473, 5.594), stdev = 0.105
  CI (99.9%): [3.564, 7.383] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.815 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.408 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.428 ±(99.9%) 0.009 ms/op
Iteration   1: 5.098 ±(99.9%) 0.021 ms/op
Iteration   2: 5.186 ±(99.9%) 0.018 ms/op
Iteration   3: 5.311 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.198 ±(99.9%) 1.952 ms/op [Average]
  (min, avg, max) = (5.098, 5.198, 5.311), stdev = 0.107
  CI (99.9%): [3.246, 7.150] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 18.201 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.011 ms/op
Iteration   1: 5.591 ±(99.9%) 0.009 ms/op
Iteration   2: 5.486 ±(99.9%) 0.017 ms/op
Iteration   3: 5.353 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.477 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (5.353, 5.477, 5.591), stdev = 0.119
  CI (99.9%): [3.302, 7.652] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 21.260 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 7.812 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.709 ±(99.9%) 0.009 ms/op
Iteration   1: 6.535 ±(99.9%) 0.011 ms/op
Iteration   2: 6.579 ±(99.9%) 0.014 ms/op
Iteration   3: 6.345 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.486 ±(99.9%) 2.266 ms/op [Average]
  (min, avg, max) = (6.345, 6.486, 6.579), stdev = 0.124
  CI (99.9%): [4.220, 8.753] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.848 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 7.404 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.092 ±(99.9%) 0.028 ms/op
Iteration   1: 5.716 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.318 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.405 ms/op
                 createUser·p0.99:   11.174 ms/op
                 createUser·p0.999:  23.597 ms/op
                 createUser·p0.9999: 27.027 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 5.756 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   9.044 ms/op
                 createUser·p0.99:   12.948 ms/op
                 createUser·p0.999:  20.560 ms/op
                 createUser·p0.9999: 36.504 ms/op
                 createUser·p1.00:   38.207 ms/op

Iteration   3: 6.093 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   8.585 ms/op
                 createUser·p0.95:   10.633 ms/op
                 createUser·p0.99:   15.827 ms/op
                 createUser·p0.999:  31.764 ms/op
                 createUser·p0.9999: 49.856 ms/op
                 createUser·p1.00:   53.346 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164059
  mean =      5.850 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 52239 
    [ 5.000, 10.000) = 105887 
    [10.000, 15.000) = 4927 
    [15.000, 20.000) = 673 
    [20.000, 25.000) = 158 
    [25.000, 30.000) = 81 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 27 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      9.241 ms/op
     p(99.0000) =     13.599 ms/op
     p(99.9000) =     25.494 ms/op
     p(99.9900) =     48.890 ms/op
     p(99.9990) =     51.667 ms/op
     p(99.9999) =     53.346 ms/op
    p(100.0000) =     53.346 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.496 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 6.281 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.021 ms/op
Iteration   1: 5.348 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.712 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  15.286 ms/op
                 existUser·p0.9999: 29.630 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   2: 5.326 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.447 ms/op
                 existUser·p0.99:   10.553 ms/op
                 existUser·p0.999:  27.623 ms/op
                 existUser·p0.9999: 32.244 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   3: 5.424 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.701 ms/op
                 existUser·p0.95:   7.791 ms/op
                 existUser·p0.99:   11.010 ms/op
                 existUser·p0.999:  28.490 ms/op
                 existUser·p0.9999: 31.162 ms/op
                 existUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178678
  mean =      5.366 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 84401 
    [ 5.000,  7.500) = 84435 
    [ 7.500, 10.000) = 7321 
    [10.000, 12.500) = 1623 
    [12.500, 15.000) = 451 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      5.050 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     18.295 ms/op
     p(99.9900) =     31.311 ms/op
     p(99.9990) =     32.618 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.752 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 7.505 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.022 ms/op
Iteration   1: 5.650 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   7.274 ms/op
                 getUser·p0.95:   8.897 ms/op
                 getUser·p0.99:   13.651 ms/op
                 getUser·p0.999:  28.376 ms/op
                 getUser·p0.9999: 36.699 ms/op
                 getUser·p1.00:   38.142 ms/op

Iteration   2: 5.496 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.761 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.340 ms/op
                 getUser·p0.99:   9.804 ms/op
                 getUser·p0.999:  15.458 ms/op
                 getUser·p0.9999: 50.934 ms/op
                 getUser·p1.00:   51.773 ms/op

Iteration   3: 5.543 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.572 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.709 ms/op
                 getUser·p0.99:   10.146 ms/op
                 getUser·p0.999:  28.715 ms/op
                 getUser·p0.9999: 32.834 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172511
  mean =      5.562 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64434 
    [ 5.000, 10.000) = 105365 
    [10.000, 15.000) = 2196 
    [15.000, 20.000) = 311 
    [20.000, 25.000) = 13 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 18 
    [50.000, 55.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.946 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     26.182 ms/op
     p(99.9900) =     49.660 ms/op
     p(99.9990) =     51.678 ms/op
     p(99.9999) =     51.773 ms/op
    p(100.0000) =     51.773 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.840 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.845 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.527 ±(99.9%) 0.025 ms/op
Iteration   1: 6.320 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.183 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  28.443 ms/op
                 listUser·p0.9999: 32.440 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   2: 6.440 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.042 ms/op
                 listUser·p0.999:  28.934 ms/op
                 listUser·p0.9999: 31.436 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   3: 6.357 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   12.601 ms/op
                 listUser·p0.999:  23.003 ms/op
                 listUser·p0.9999: 30.735 ms/op
                 listUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150578
  mean =      6.372 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 7835 
    [ 5.000,  7.500) = 123844 
    [ 7.500, 10.000) = 14278 
    [10.000, 12.500) = 3145 
    [12.500, 15.000) = 915 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 107 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      7.815 ms/op
     p(95.0000) =      8.995 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     28.227 ms/op
     p(99.9900) =     31.419 ms/op
     p(99.9990) =     33.782 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.712 ± 3.518  ops/ms
ClientPb.existUser                       thrpt       3   6.251 ± 1.099  ops/ms
ClientPb.getUser                         thrpt       3   5.615 ± 2.991  ops/ms
ClientPb.listUser                        thrpt       3   4.864 ± 1.497  ops/ms
ClientPb.createUser                       avgt       3   5.473 ± 1.909   ms/op
ClientPb.existUser                        avgt       3   5.198 ± 1.952   ms/op
ClientPb.getUser                          avgt       3   5.477 ± 2.175   ms/op
ClientPb.listUser                         avgt       3   6.486 ± 2.266   ms/op
ClientPb.createUser                     sample  164059   5.850 ± 0.016   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.472           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.599           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.494           ms/op
ClientPb.createUser:createUser·p0.9999  sample          48.890           ms/op
ClientPb.createUser:createUser·p1.00    sample          53.346           ms/op
ClientPb.existUser                      sample  178678   5.366 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.050           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.660           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.676           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.584           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.295           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.311           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.030           ms/op
ClientPb.getUser                        sample  172511   5.562 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.946           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.076           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.182           ms/op
ClientPb.getUser:getUser·p0.9999        sample          49.660           ms/op
ClientPb.getUser:getUser·p1.00          sample          51.773           ms/op
ClientPb.listUser                       sample  150578   6.372 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.281           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.452           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.227           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.419           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.948           ms/op
