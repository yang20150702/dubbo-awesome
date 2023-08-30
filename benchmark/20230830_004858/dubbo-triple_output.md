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
# Warmup Iteration   1: 0.941 ops/ms
# Warmup Iteration   2: 2.123 ops/ms
# Warmup Iteration   3: 4.503 ops/ms
Iteration   1: 5.088 ops/ms
Iteration   2: 5.528 ops/ms
Iteration   3: 5.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.315 ±(99.9%) 4.016 ops/ms [Average]
  (min, avg, max) = (5.088, 5.315, 5.528), stdev = 0.220
  CI (99.9%): [1.299, 9.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.442 ops/ms
# Warmup Iteration   2: 4.390 ops/ms
# Warmup Iteration   3: 5.341 ops/ms
Iteration   1: 5.419 ops/ms
Iteration   2: 5.684 ops/ms
Iteration   3: 5.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.570 ±(99.9%) 2.485 ops/ms [Average]
  (min, avg, max) = (5.419, 5.570, 5.684), stdev = 0.136
  CI (99.9%): [3.085, 8.055] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.267 ops/ms
# Warmup Iteration   2: 4.308 ops/ms
# Warmup Iteration   3: 5.280 ops/ms
Iteration   1: 5.546 ops/ms
Iteration   2: 5.384 ops/ms
Iteration   3: 5.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.510 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (5.384, 5.510, 5.600), stdev = 0.112
  CI (99.9%): [3.461, 7.559] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.518 ops/ms
# Warmup Iteration   2: 3.458 ops/ms
# Warmup Iteration   3: 4.203 ops/ms
Iteration   1: 4.178 ops/ms
Iteration   2: 4.575 ops/ms
Iteration   3: 4.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.489 ±(99.9%) 5.076 ops/ms [Average]
  (min, avg, max) = (4.178, 4.489, 4.714), stdev = 0.278
  CI (99.9%): [≈ 0, 9.564] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.643 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 8.297 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.335 ±(99.9%) 0.012 ms/op
Iteration   1: 6.139 ±(99.9%) 0.015 ms/op
Iteration   2: 5.867 ±(99.9%) 0.016 ms/op
Iteration   3: 5.915 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.974 ±(99.9%) 2.641 ms/op [Average]
  (min, avg, max) = (5.867, 5.974, 6.139), stdev = 0.145
  CI (99.9%): [3.333, 8.615] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.833 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.888 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.960 ±(99.9%) 0.009 ms/op
Iteration   1: 5.692 ±(99.9%) 0.017 ms/op
Iteration   2: 5.709 ±(99.9%) 0.022 ms/op
Iteration   3: 5.535 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.646 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (5.535, 5.646, 5.709), stdev = 0.096
  CI (99.9%): [3.896, 7.395] (assumes normal distribution)


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
# Warmup Iteration   1: 18.843 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 7.813 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.072 ±(99.9%) 0.009 ms/op
Iteration   1: 6.060 ±(99.9%) 0.018 ms/op
Iteration   2: 6.140 ±(99.9%) 0.011 ms/op
Iteration   3: 5.761 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.987 ±(99.9%) 3.644 ms/op [Average]
  (min, avg, max) = (5.761, 5.987, 6.140), stdev = 0.200
  CI (99.9%): [2.343, 9.631] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.608 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 9.164 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 7.273 ±(99.9%) 0.011 ms/op
Iteration   1: 7.005 ±(99.9%) 0.014 ms/op
Iteration   2: 6.873 ±(99.9%) 0.012 ms/op
Iteration   3: 6.983 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.954 ±(99.9%) 1.291 ms/op [Average]
  (min, avg, max) = (6.873, 6.954, 7.005), stdev = 0.071
  CI (99.9%): [5.663, 8.244] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 21.721 ±(99.9%) 0.401 ms/op
# Warmup Iteration   2: 7.864 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.896 ±(99.9%) 0.036 ms/op
Iteration   1: 6.196 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.916 ms/op
                 createUser·p0.50:   5.849 ms/op
                 createUser·p0.90:   7.635 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   11.829 ms/op
                 createUser·p0.999:  29.283 ms/op
                 createUser·p0.9999: 53.150 ms/op
                 createUser·p1.00:   53.477 ms/op

Iteration   2: 6.092 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.478 ms/op
                 createUser·p0.50:   5.808 ms/op
                 createUser·p0.90:   7.381 ms/op
                 createUser·p0.95:   8.200 ms/op
                 createUser·p0.99:   11.548 ms/op
                 createUser·p0.999:  29.096 ms/op
                 createUser·p0.9999: 32.415 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 6.014 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.617 ms/op
                 createUser·p0.50:   5.669 ms/op
                 createUser·p0.90:   7.422 ms/op
                 createUser·p0.95:   8.385 ms/op
                 createUser·p0.99:   11.780 ms/op
                 createUser·p0.999:  31.154 ms/op
                 createUser·p0.9999: 34.713 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157453
  mean =      6.100 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 19257 
    [ 5.000, 10.000) = 134973 
    [10.000, 15.000) = 2824 
    [15.000, 20.000) = 168 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 53 
    [30.000, 35.000) = 119 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 12 
    [50.000, 55.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.478 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     29.822 ms/op
     p(99.9900) =     50.201 ms/op
     p(99.9990) =     53.402 ms/op
     p(99.9999) =     53.477 ms/op
    p(100.0000) =     53.477 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.595 ±(99.9%) 0.381 ms/op
# Warmup Iteration   2: 7.036 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.703 ±(99.9%) 0.021 ms/op
Iteration   1: 5.826 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.081 ms/op
                 existUser·p0.50:   5.513 ms/op
                 existUser·p0.90:   7.242 ms/op
                 existUser·p0.95:   8.389 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  25.988 ms/op
                 existUser·p0.9999: 41.453 ms/op
                 existUser·p1.00:   47.055 ms/op

Iteration   2: 5.529 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.736 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.373 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  26.980 ms/op
                 existUser·p0.9999: 30.154 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   3: 5.735 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   5.456 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   7.928 ms/op
                 existUser·p0.99:   10.478 ms/op
                 existUser·p0.999:  17.572 ms/op
                 existUser·p0.9999: 35.979 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168436
  mean =      5.694 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 43959 
    [ 5.000, 10.000) = 121967 
    [10.000, 15.000) = 2109 
    [15.000, 20.000) = 237 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 86 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     35.990 ms/op
     p(99.9990) =     46.561 ms/op
     p(99.9999) =     47.055 ms/op
    p(100.0000) =     47.055 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.934 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 8.054 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.144 ±(99.9%) 0.026 ms/op
Iteration   1: 6.010 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.894 ms/op
                 getUser·p0.50:   5.661 ms/op
                 getUser·p0.90:   7.545 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   12.009 ms/op
                 getUser·p0.999:  27.034 ms/op
                 getUser·p0.9999: 30.836 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   2: 5.979 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.761 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   7.307 ms/op
                 getUser·p0.95:   8.534 ms/op
                 getUser·p0.99:   12.616 ms/op
                 getUser·p0.999:  28.840 ms/op
                 getUser·p0.9999: 36.153 ms/op
                 getUser·p1.00:   36.307 ms/op

Iteration   3: 5.879 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   12.224 ms/op
                 getUser·p0.999:  18.305 ms/op
                 getUser·p0.9999: 31.516 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 161011
  mean =      5.956 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 30748 
    [ 5.000,  7.500) = 115500 
    [ 7.500, 10.000) = 9991 
    [10.000, 12.500) = 3323 
    [12.500, 15.000) = 972 
    [15.000, 17.500) = 223 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     36.267 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 22.913 ±(99.9%) 0.402 ms/op
# Warmup Iteration   2: 9.524 ±(99.9%) 0.085 ms/op
# Warmup Iteration   3: 7.296 ±(99.9%) 0.033 ms/op
Iteration   1: 6.783 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  29.426 ms/op
                 listUser·p0.9999: 32.276 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   2: 6.890 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   8.448 ms/op
                 listUser·p0.95:   10.109 ms/op
                 listUser·p0.99:   14.031 ms/op
                 listUser·p0.999:  33.244 ms/op
                 listUser·p0.9999: 38.404 ms/op
                 listUser·p1.00:   39.911 ms/op

Iteration   3: 7.089 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.174 ms/op
                 listUser·p0.50:   6.734 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   13.238 ms/op
                 listUser·p0.999:  29.557 ms/op
                 listUser·p0.9999: 40.532 ms/op
                 listUser·p1.00:   42.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138743
  mean =      6.918 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1824 
    [ 5.000, 10.000) = 130246 
    [10.000, 15.000) = 5833 
    [15.000, 20.000) = 488 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 125 
    [30.000, 35.000) = 105 
    [35.000, 40.000) = 54 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      6.529 ms/op
     p(90.0000) =      8.331 ms/op
     p(95.0000) =      9.912 ms/op
     p(99.0000) =     13.468 ms/op
     p(99.9000) =     30.867 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     41.928 ms/op
     p(99.9999) =     42.664 ms/op
    p(100.0000) =     42.664 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.315 ± 4.016  ops/ms
ClientPb.existUser                       thrpt       3   5.570 ± 2.485  ops/ms
ClientPb.getUser                         thrpt       3   5.510 ± 2.049  ops/ms
ClientPb.listUser                        thrpt       3   4.489 ± 5.076  ops/ms
ClientPb.createUser                       avgt       3   5.974 ± 2.641   ms/op
ClientPb.existUser                        avgt       3   5.646 ± 1.750   ms/op
ClientPb.getUser                          avgt       3   5.987 ± 3.644   ms/op
ClientPb.listUser                         avgt       3   6.954 ± 1.291   ms/op
ClientPb.createUser                     sample  157453   6.100 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.478           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.479           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.438           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.731           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          50.201           ms/op
ClientPb.createUser:createUser·p1.00    sample          53.477           ms/op
ClientPb.existUser                      sample  168436   5.694 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.938           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.879           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.990           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.055           ms/op
ClientPb.getUser                        sample  161011   5.956 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.894           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.595           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.765           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.272           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.492           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.045           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  138743   6.918 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.519           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.331           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.912           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.867           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.404           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.664           ms/op
