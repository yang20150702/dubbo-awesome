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
# Warmup Iteration   1: 1.197 ops/ms
# Warmup Iteration   2: 2.424 ops/ms
# Warmup Iteration   3: 4.944 ops/ms
Iteration   1: 5.660 ops/ms
Iteration   2: 6.031 ops/ms
Iteration   3: 5.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.882 ±(99.9%) 3.570 ops/ms [Average]
  (min, avg, max) = (5.660, 5.882, 6.031), stdev = 0.196
  CI (99.9%): [2.311, 9.452] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.559 ops/ms
# Warmup Iteration   2: 4.866 ops/ms
# Warmup Iteration   3: 6.011 ops/ms
Iteration   1: 5.961 ops/ms
Iteration   2: 6.277 ops/ms
Iteration   3: 6.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.152 ±(99.9%) 3.061 ops/ms [Average]
  (min, avg, max) = (5.961, 6.152, 6.277), stdev = 0.168
  CI (99.9%): [3.091, 9.212] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.390 ops/ms
# Warmup Iteration   2: 4.354 ops/ms
# Warmup Iteration   3: 5.481 ops/ms
Iteration   1: 5.717 ops/ms
Iteration   2: 5.685 ops/ms
Iteration   3: 5.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.766 ±(99.9%) 2.053 ops/ms [Average]
  (min, avg, max) = (5.685, 5.766, 5.894), stdev = 0.113
  CI (99.9%): [3.712, 7.819] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.566 ops/ms
# Warmup Iteration   2: 4.127 ops/ms
# Warmup Iteration   3: 4.867 ops/ms
Iteration   1: 5.003 ops/ms
Iteration   2: 5.249 ops/ms
Iteration   3: 4.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.066 ±(99.9%) 2.929 ops/ms [Average]
  (min, avg, max) = (4.947, 5.066, 5.249), stdev = 0.161
  CI (99.9%): [2.138, 7.995] (assumes normal distribution)


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
# Warmup Iteration   1: 15.992 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.271 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.712 ±(99.9%) 0.014 ms/op
Iteration   1: 5.525 ±(99.9%) 0.008 ms/op
Iteration   2: 5.681 ±(99.9%) 0.005 ms/op
Iteration   3: 5.485 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.564 ±(99.9%) 1.890 ms/op [Average]
  (min, avg, max) = (5.485, 5.564, 5.681), stdev = 0.104
  CI (99.9%): [3.674, 7.454] (assumes normal distribution)


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
# Warmup Iteration   1: 16.328 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.319 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.011 ms/op
Iteration   1: 5.493 ±(99.9%) 0.007 ms/op
Iteration   2: 5.331 ±(99.9%) 0.010 ms/op
Iteration   3: 5.256 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.360 ±(99.9%) 2.211 ms/op [Average]
  (min, avg, max) = (5.256, 5.360, 5.493), stdev = 0.121
  CI (99.9%): [3.149, 7.571] (assumes normal distribution)


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
# Warmup Iteration   1: 17.598 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.116 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.434 ±(99.9%) 0.011 ms/op
Iteration   1: 5.517 ±(99.9%) 0.012 ms/op
Iteration   2: 5.500 ±(99.9%) 0.010 ms/op
Iteration   3: 5.402 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.473 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (5.402, 5.473, 5.517), stdev = 0.062
  CI (99.9%): [4.341, 6.605] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.110 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 8.826 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.382 ±(99.9%) 0.017 ms/op
Iteration   1: 6.281 ±(99.9%) 0.015 ms/op
Iteration   2: 6.230 ±(99.9%) 0.017 ms/op
Iteration   3: 6.472 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.327 ±(99.9%) 2.327 ms/op [Average]
  (min, avg, max) = (6.230, 6.327, 6.472), stdev = 0.128
  CI (99.9%): [4.000, 8.654] (assumes normal distribution)


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
# Warmup Iteration   1: 15.608 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 6.555 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.872 ±(99.9%) 0.026 ms/op
Iteration   1: 5.463 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   5.104 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   10.367 ms/op
                 createUser·p0.999:  24.360 ms/op
                 createUser·p0.9999: 30.287 ms/op
                 createUser·p1.00:   31.326 ms/op

Iteration   2: 5.398 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.810 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.652 ms/op
                 createUser·p0.95:   7.455 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 31.741 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   3: 5.757 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   6.963 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  27.969 ms/op
                 createUser·p0.9999: 32.702 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173340
  mean =      5.535 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 66304 
    [ 5.000,  7.500) = 96354 
    [ 7.500, 10.000) = 8339 
    [10.000, 12.500) = 1638 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     32.080 ms/op
     p(99.9990) =     33.360 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 15.275 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.018 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.025 ms/op
Iteration   1: 5.479 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.130 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   7.045 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   10.830 ms/op
                 existUser·p0.999:  23.697 ms/op
                 existUser·p0.9999: 33.489 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   2: 5.476 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.384 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   7.033 ms/op
                 existUser·p0.95:   8.249 ms/op
                 existUser·p0.99:   10.830 ms/op
                 existUser·p0.999:  14.492 ms/op
                 existUser·p0.9999: 30.217 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   3: 5.402 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  28.637 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176079
  mean =      5.452 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 76129 
    [ 5.000,  7.500) = 87630 
    [ 7.500, 10.000) = 9548 
    [10.000, 12.500) = 1888 
    [12.500, 15.000) = 501 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     21.166 ms/op
     p(99.9900) =     32.433 ms/op
     p(99.9990) =     34.270 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 17.265 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.158 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.684 ±(99.9%) 0.019 ms/op
Iteration   1: 5.534 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.017 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.135 ms/op
                 getUser·p0.99:   11.010 ms/op
                 getUser·p0.999:  24.762 ms/op
                 getUser·p0.9999: 28.183 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   2: 5.783 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.823 ms/op
                 getUser·p0.95:   8.968 ms/op
                 getUser·p0.99:   11.886 ms/op
                 getUser·p0.999:  18.514 ms/op
                 getUser·p0.9999: 28.353 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 5.624 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.425 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   7.750 ms/op
                 getUser·p0.99:   10.171 ms/op
                 getUser·p0.999:  25.939 ms/op
                 getUser·p0.9999: 30.653 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169941
  mean =      5.645 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 59348 
    [ 5.000,  7.500) = 96750 
    [ 7.500, 10.000) = 10924 
    [10.000, 12.500) = 2075 
    [12.500, 15.000) = 512 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.017 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     18.844 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     32.431 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 19.584 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 7.174 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.367 ±(99.9%) 0.023 ms/op
Iteration   1: 6.543 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   8.282 ms/op
                 listUser·p0.95:   9.375 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  24.384 ms/op
                 listUser·p0.9999: 27.481 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 6.637 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  28.672 ms/op
                 listUser·p0.9999: 36.060 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   3: 6.384 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  21.811 ms/op
                 listUser·p0.9999: 25.066 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147271
  mean =      6.520 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 5859 
    [ 5.000,  7.500) = 121471 
    [ 7.500, 10.000) = 15154 
    [10.000, 12.500) = 3509 
    [12.500, 15.000) = 732 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      7.954 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     12.222 ms/op
     p(99.9000) =     25.386 ms/op
     p(99.9900) =     35.473 ms/op
     p(99.9990) =     36.573 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.882 ± 3.570  ops/ms
ClientPb.existUser                       thrpt       3   6.152 ± 3.061  ops/ms
ClientPb.getUser                         thrpt       3   5.766 ± 2.053  ops/ms
ClientPb.listUser                        thrpt       3   5.066 ± 2.929  ops/ms
ClientPb.createUser                       avgt       3   5.564 ± 1.890   ms/op
ClientPb.existUser                        avgt       3   5.360 ± 2.211   ms/op
ClientPb.getUser                          avgt       3   5.473 ± 1.132   ms/op
ClientPb.listUser                         avgt       3   6.327 ± 2.327   ms/op
ClientPb.createUser                     sample  173340   5.535 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.226           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.840           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.535           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.412           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.080           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  176079   5.452 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.077           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.895           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.166           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.433           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  169941   5.645 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.017           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.184           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.356           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.092           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.844           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.360           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.866           ms/op
ClientPb.listUser                       sample  147271   6.520 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.937           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.954           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.191           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.222           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.386           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.473           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.635           ms/op
