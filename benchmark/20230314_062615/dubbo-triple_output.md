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
# Warmup Iteration   1: 1.054 ops/ms
# Warmup Iteration   2: 2.486 ops/ms
# Warmup Iteration   3: 5.138 ops/ms
Iteration   1: 5.176 ops/ms
Iteration   2: 5.510 ops/ms
Iteration   3: 5.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.400 ±(99.9%) 3.543 ops/ms [Average]
  (min, avg, max) = (5.176, 5.400, 5.514), stdev = 0.194
  CI (99.9%): [1.857, 8.943] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.534 ops/ms
# Warmup Iteration   2: 4.326 ops/ms
# Warmup Iteration   3: 5.383 ops/ms
Iteration   1: 5.856 ops/ms
Iteration   2: 5.792 ops/ms
Iteration   3: 6.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.884 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (5.792, 5.884, 6.005), stdev = 0.110
  CI (99.9%): [3.884, 7.885] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.533 ops/ms
# Warmup Iteration   2: 4.148 ops/ms
# Warmup Iteration   3: 5.447 ops/ms
Iteration   1: 5.442 ops/ms
Iteration   2: 5.673 ops/ms
Iteration   3: 5.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.637 ±(99.9%) 3.290 ops/ms [Average]
  (min, avg, max) = (5.442, 5.637, 5.797), stdev = 0.180
  CI (99.9%): [2.347, 8.927] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.748 ops/ms
# Warmup Iteration   2: 4.041 ops/ms
# Warmup Iteration   3: 4.711 ops/ms
Iteration   1: 4.743 ops/ms
Iteration   2: 4.777 ops/ms
Iteration   3: 4.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.786 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (4.743, 4.786, 4.838), stdev = 0.048
  CI (99.9%): [3.903, 5.669] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.421 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.797 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.348 ±(99.9%) 0.013 ms/op
Iteration   1: 5.904 ±(99.9%) 0.016 ms/op
Iteration   2: 5.585 ±(99.9%) 0.023 ms/op
Iteration   3: 5.675 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.721 ±(99.9%) 3.004 ms/op [Average]
  (min, avg, max) = (5.585, 5.721, 5.904), stdev = 0.165
  CI (99.9%): [2.717, 8.726] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.815 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.639 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.431 ±(99.9%) 0.013 ms/op
Iteration   1: 5.324 ±(99.9%) 0.010 ms/op
Iteration   2: 5.302 ±(99.9%) 0.013 ms/op
Iteration   3: 5.442 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.356 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (5.302, 5.356, 5.442), stdev = 0.075
  CI (99.9%): [3.984, 6.728] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.172 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.272 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.910 ±(99.9%) 0.010 ms/op
Iteration   1: 5.565 ±(99.9%) 0.013 ms/op
Iteration   2: 5.660 ±(99.9%) 0.015 ms/op
Iteration   3: 6.119 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.781 ±(99.9%) 5.409 ms/op [Average]
  (min, avg, max) = (5.565, 5.781, 6.119), stdev = 0.296
  CI (99.9%): [0.373, 11.190] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.031 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 8.535 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.865 ±(99.9%) 0.022 ms/op
Iteration   1: 6.646 ±(99.9%) 0.011 ms/op
Iteration   2: 6.509 ±(99.9%) 0.014 ms/op
Iteration   3: 6.422 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.525 ±(99.9%) 2.059 ms/op [Average]
  (min, avg, max) = (6.422, 6.525, 6.646), stdev = 0.113
  CI (99.9%): [4.467, 8.584] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.165 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 7.064 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.139 ±(99.9%) 0.028 ms/op
Iteration   1: 5.608 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   11.796 ms/op
                 createUser·p0.999:  26.738 ms/op
                 createUser·p0.9999: 31.270 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   2: 5.658 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  27.313 ms/op
                 createUser·p0.9999: 31.337 ms/op
                 createUser·p1.00:   32.342 ms/op

Iteration   3: 5.611 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  14.958 ms/op
                 createUser·p0.9999: 37.997 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170665
  mean =      5.625 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 56285 
    [ 5.000,  7.500) = 103609 
    [ 7.500, 10.000) = 8177 
    [10.000, 12.500) = 1662 
    [12.500, 15.000) = 522 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.322 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     25.330 ms/op
     p(99.9900) =     36.359 ms/op
     p(99.9990) =     38.770 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.186 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.256 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.416 ±(99.9%) 0.020 ms/op
Iteration   1: 5.620 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   1.890 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   7.332 ms/op
                 existUser·p0.95:   8.765 ms/op
                 existUser·p0.99:   12.599 ms/op
                 existUser·p0.999:  28.541 ms/op
                 existUser·p0.9999: 37.376 ms/op
                 existUser·p1.00:   38.339 ms/op

Iteration   2: 5.687 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.036 ms/op
                 existUser·p0.50:   5.358 ms/op
                 existUser·p0.90:   7.127 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   11.092 ms/op
                 existUser·p0.999:  14.590 ms/op
                 existUser·p0.9999: 32.260 ms/op
                 existUser·p1.00:   32.670 ms/op

Iteration   3: 5.544 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   8.143 ms/op
                 existUser·p0.99:   12.075 ms/op
                 existUser·p0.999:  29.360 ms/op
                 existUser·p0.9999: 32.619 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170851
  mean =      5.616 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 62491 
    [ 5.000,  7.500) = 94588 
    [ 7.500, 10.000) = 9887 
    [10.000, 12.500) = 2488 
    [12.500, 15.000) = 777 
    [15.000, 17.500) = 287 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.078 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     26.023 ms/op
     p(99.9900) =     36.039 ms/op
     p(99.9990) =     38.246 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.215 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.789 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.709 ±(99.9%) 0.024 ms/op
Iteration   1: 5.747 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.364 ms/op
                 getUser·p0.99:   11.567 ms/op
                 getUser·p0.999:  25.906 ms/op
                 getUser·p0.9999: 28.719 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   2: 5.485 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.601 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.143 ms/op
                 getUser·p0.99:   11.464 ms/op
                 getUser·p0.999:  16.302 ms/op
                 getUser·p0.9999: 30.026 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   3: 5.326 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.806 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  25.330 ms/op
                 getUser·p0.9999: 42.008 ms/op
                 getUser·p1.00:   44.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174056
  mean =      5.514 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 71706 
    [ 5.000, 10.000) = 99024 
    [10.000, 15.000) = 2870 
    [15.000, 20.000) = 208 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 137 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     25.000 ms/op
     p(99.9900) =     40.174 ms/op
     p(99.9990) =     44.713 ms/op
     p(99.9999) =     44.761 ms/op
    p(100.0000) =     44.761 ms/op


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
# Warmup Iteration   1: 20.047 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.639 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.167 ±(99.9%) 0.022 ms/op
Iteration   1: 6.519 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   8.118 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  28.602 ms/op
                 listUser·p0.9999: 44.767 ms/op
                 listUser·p1.00:   46.137 ms/op

Iteration   2: 6.472 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  28.549 ms/op
                 listUser·p0.9999: 40.975 ms/op
                 listUser·p1.00:   46.399 ms/op

Iteration   3: 6.179 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  20.299 ms/op
                 listUser·p0.9999: 25.154 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150306
  mean =      6.386 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10370 
    [ 5.000, 10.000) = 135587 
    [10.000, 15.000) = 3746 
    [15.000, 20.000) = 302 
    [20.000, 25.000) = 111 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      6.038 ms/op
     p(90.0000) =      7.856 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.370 ms/op
     p(99.9000) =     26.532 ms/op
     p(99.9900) =     42.791 ms/op
     p(99.9990) =     46.268 ms/op
     p(99.9999) =     46.399 ms/op
    p(100.0000) =     46.399 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.400 ± 3.543  ops/ms
ClientPb.existUser                       thrpt       3   5.884 ± 2.001  ops/ms
ClientPb.getUser                         thrpt       3   5.637 ± 3.290  ops/ms
ClientPb.listUser                        thrpt       3   4.786 ± 0.883  ops/ms
ClientPb.createUser                       avgt       3   5.721 ± 3.004   ms/op
ClientPb.existUser                        avgt       3   5.356 ± 1.372   ms/op
ClientPb.getUser                          avgt       3   5.781 ± 5.409   ms/op
ClientPb.listUser                         avgt       3   6.525 ± 2.059   ms/op
ClientPb.createUser                     sample  170665   5.625 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.322           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.856           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.912           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.330           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.359           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  170851   5.616 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.078           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.454           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.796           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.023           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  174056   5.514 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.020           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.305           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.000           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.174           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.761           ms/op
ClientPb.listUser                       sample  150306   6.386 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.126           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.370           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.532           ms/op
ClientPb.listUser:listUser·p0.9999      sample          42.791           ms/op
ClientPb.listUser:listUser·p1.00        sample          46.399           ms/op
