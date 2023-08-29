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
# Warmup Iteration   1: 1.207 ops/ms
# Warmup Iteration   2: 2.785 ops/ms
# Warmup Iteration   3: 5.658 ops/ms
Iteration   1: 5.865 ops/ms
Iteration   2: 6.164 ops/ms
Iteration   3: 6.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.067 ±(99.9%) 3.184 ops/ms [Average]
  (min, avg, max) = (5.865, 6.067, 6.171), stdev = 0.175
  CI (99.9%): [2.883, 9.251] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.712 ops/ms
# Warmup Iteration   2: 4.887 ops/ms
# Warmup Iteration   3: 6.013 ops/ms
Iteration   1: 6.333 ops/ms
Iteration   2: 6.353 ops/ms
Iteration   3: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.367 ±(99.9%) 0.777 ops/ms [Average]
  (min, avg, max) = (6.333, 6.367, 6.415), stdev = 0.043
  CI (99.9%): [5.590, 7.144] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.484 ops/ms
# Warmup Iteration   2: 4.418 ops/ms
# Warmup Iteration   3: 5.983 ops/ms
Iteration   1: 5.851 ops/ms
Iteration   2: 5.954 ops/ms
Iteration   3: 5.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.868 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (5.801, 5.868, 5.954), stdev = 0.078
  CI (99.9%): [4.448, 7.289] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.642 ops/ms
# Warmup Iteration   2: 4.406 ops/ms
# Warmup Iteration   3: 5.393 ops/ms
Iteration   1: 5.378 ops/ms
Iteration   2: 5.274 ops/ms
Iteration   3: 5.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.281 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (5.192, 5.281, 5.378), stdev = 0.093
  CI (99.9%): [3.581, 6.982] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.718 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.815 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.082 ±(99.9%) 0.008 ms/op
Iteration   1: 5.517 ±(99.9%) 0.011 ms/op
Iteration   2: 5.295 ±(99.9%) 0.017 ms/op
Iteration   3: 5.347 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.387 ±(99.9%) 2.116 ms/op [Average]
  (min, avg, max) = (5.295, 5.387, 5.517), stdev = 0.116
  CI (99.9%): [3.271, 7.502] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.617 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.883 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.224 ±(99.9%) 0.005 ms/op
Iteration   1: 5.103 ±(99.9%) 0.009 ms/op
Iteration   2: 5.138 ±(99.9%) 0.005 ms/op
Iteration   3: 5.090 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.110 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (5.090, 5.110, 5.138), stdev = 0.025
  CI (99.9%): [4.656, 5.565] (assumes normal distribution)


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
# Warmup Iteration   1: 15.887 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.255 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.443 ±(99.9%) 0.012 ms/op
Iteration   1: 5.429 ±(99.9%) 0.008 ms/op
Iteration   2: 5.463 ±(99.9%) 0.019 ms/op
Iteration   3: 5.355 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.416 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (5.355, 5.416, 5.463), stdev = 0.055
  CI (99.9%): [4.416, 6.415] (assumes normal distribution)


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
# Warmup Iteration   1: 18.661 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.251 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.209 ±(99.9%) 0.021 ms/op
Iteration   1: 6.289 ±(99.9%) 0.019 ms/op
Iteration   2: 6.261 ±(99.9%) 0.010 ms/op
Iteration   3: 6.113 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.221 ±(99.9%) 1.724 ms/op [Average]
  (min, avg, max) = (6.113, 6.221, 6.289), stdev = 0.095
  CI (99.9%): [4.497, 7.945] (assumes normal distribution)


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
# Warmup Iteration   1: 16.357 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.829 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.739 ±(99.9%) 0.024 ms/op
Iteration   1: 5.662 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.023 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   11.125 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 38.624 ms/op
                 createUser·p1.00:   40.370 ms/op

Iteration   2: 5.249 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.034 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.406 ms/op
                 createUser·p0.95:   7.094 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  25.923 ms/op
                 createUser·p0.9999: 29.357 ms/op
                 createUser·p1.00:   35.324 ms/op

Iteration   3: 5.343 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  27.955 ms/op
                 createUser·p0.9999: 32.998 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177274
  mean =      5.413 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 81580 
    [ 5.000, 10.000) = 93127 
    [10.000, 15.000) = 2100 
    [15.000, 20.000) = 187 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 162 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     26.435 ms/op
     p(99.9900) =     37.051 ms/op
     p(99.9990) =     39.155 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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
# Warmup Iteration   1: 13.846 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.694 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.279 ±(99.9%) 0.020 ms/op
Iteration   1: 5.064 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  23.740 ms/op
                 existUser·p0.9999: 28.049 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   2: 5.391 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.862 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   8.036 ms/op
                 existUser·p0.99:   10.455 ms/op
                 existUser·p0.999:  26.622 ms/op
                 existUser·p0.9999: 36.110 ms/op
                 existUser·p1.00:   38.076 ms/op

Iteration   3: 5.060 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.597 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.898 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  27.296 ms/op
                 existUser·p0.9999: 33.128 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185743
  mean =      5.167 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 99557 
    [ 5.000,  7.500) = 77226 
    [ 7.500, 10.000) = 6721 
    [10.000, 12.500) = 1425 
    [12.500, 15.000) = 523 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.315 ms/op
     p(99.9000) =     24.822 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     37.177 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 16.559 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.608 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.622 ±(99.9%) 0.023 ms/op
Iteration   1: 5.325 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  31.043 ms/op
                 getUser·p0.9999: 43.319 ms/op
                 getUser·p1.00:   44.827 ms/op

Iteration   2: 5.612 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.036 ms/op
                 getUser·p0.99:   10.293 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 29.960 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 5.461 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   11.567 ms/op
                 getUser·p0.999:  26.640 ms/op
                 getUser·p0.9999: 29.599 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175645
  mean =      5.464 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 71921 
    [ 5.000, 10.000) = 100821 
    [10.000, 15.000) = 2454 
    [15.000, 20.000) = 247 
    [20.000, 25.000) = 9 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     26.369 ms/op
     p(99.9900) =     36.626 ms/op
     p(99.9990) =     44.380 ms/op
     p(99.9999) =     44.827 ms/op
    p(100.0000) =     44.827 ms/op


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
# Warmup Iteration   1: 18.994 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 8.078 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.340 ±(99.9%) 0.027 ms/op
Iteration   1: 6.461 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  27.867 ms/op
                 listUser·p0.9999: 30.429 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 6.235 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.177 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  31.785 ms/op
                 listUser·p0.9999: 36.620 ms/op
                 listUser·p1.00:   37.290 ms/op

Iteration   3: 6.317 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.066 ms/op
                 listUser·p0.999:  27.691 ms/op
                 listUser·p0.9999: 30.238 ms/op
                 listUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151536
  mean =      6.337 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 6298 
    [ 5.000,  7.500) = 129606 
    [ 7.500, 10.000) = 11836 
    [10.000, 12.500) = 2610 
    [12.500, 15.000) = 701 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      6.005 ms/op
     p(90.0000) =      7.537 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     28.523 ms/op
     p(99.9900) =     34.921 ms/op
     p(99.9990) =     37.222 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.067 ± 3.184  ops/ms
ClientPb.existUser                       thrpt       3   6.367 ± 0.777  ops/ms
ClientPb.getUser                         thrpt       3   5.868 ± 1.420  ops/ms
ClientPb.listUser                        thrpt       3   5.281 ± 1.700  ops/ms
ClientPb.createUser                       avgt       3   5.387 ± 2.116   ms/op
ClientPb.existUser                        avgt       3   5.110 ± 0.454   ms/op
ClientPb.getUser                          avgt       3   5.416 ± 1.000   ms/op
ClientPb.listUser                         avgt       3   6.221 ± 1.724   ms/op
ClientPb.createUser                     sample  177274   5.413 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.610           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.071           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.873           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.435           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.370           ms/op
ClientPb.existUser                      sample  185743   5.167 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.532           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.948           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.422           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.315           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.822           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.076           ms/op
ClientPb.getUser                        sample  175645   5.464 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.815           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.076           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.369           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.626           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.827           ms/op
ClientPb.listUser                       sample  151536   6.337 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.005           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.715           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.523           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.921           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.290           ms/op
