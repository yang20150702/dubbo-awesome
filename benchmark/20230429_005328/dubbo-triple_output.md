# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.927 ops/ms
# Warmup Iteration   2: 1.987 ops/ms
# Warmup Iteration   3: 4.405 ops/ms
Iteration   1: 5.082 ops/ms
Iteration   2: 5.667 ops/ms
Iteration   3: 5.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.453 ±(99.9%) 5.877 ops/ms [Average]
  (min, avg, max) = (5.082, 5.453, 5.667), stdev = 0.322
  CI (99.9%): [≈ 0, 11.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.557 ops/ms
# Warmup Iteration   2: 4.351 ops/ms
# Warmup Iteration   3: 5.814 ops/ms
Iteration   1: 5.864 ops/ms
Iteration   2: 5.867 ops/ms
Iteration   3: 6.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.915 ±(99.9%) 1.539 ops/ms [Average]
  (min, avg, max) = (5.864, 5.915, 6.012), stdev = 0.084
  CI (99.9%): [4.376, 7.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.357 ops/ms
# Warmup Iteration   2: 4.048 ops/ms
# Warmup Iteration   3: 5.612 ops/ms
Iteration   1: 5.547 ops/ms
Iteration   2: 5.510 ops/ms
Iteration   3: 5.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.568 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (5.510, 5.568, 5.648), stdev = 0.071
  CI (99.9%): [4.270, 6.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.495 ops/ms
# Warmup Iteration   2: 3.490 ops/ms
# Warmup Iteration   3: 4.471 ops/ms
Iteration   1: 4.684 ops/ms
Iteration   2: 5.111 ops/ms
Iteration   3: 4.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.858 ±(99.9%) 4.088 ops/ms [Average]
  (min, avg, max) = (4.684, 4.858, 5.111), stdev = 0.224
  CI (99.9%): [0.770, 8.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 20.147 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.519 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.783 ±(99.9%) 0.018 ms/op
Iteration   1: 5.697 ±(99.9%) 0.016 ms/op
Iteration   2: 5.455 ±(99.9%) 0.012 ms/op
Iteration   3: 5.385 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.512 ±(99.9%) 2.985 ms/op [Average]
  (min, avg, max) = (5.385, 5.512, 5.697), stdev = 0.164
  CI (99.9%): [2.527, 8.497] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.776 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 6.291 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.515 ±(99.9%) 0.010 ms/op
Iteration   1: 5.328 ±(99.9%) 0.012 ms/op
Iteration   2: 5.287 ±(99.9%) 0.015 ms/op
Iteration   3: 5.628 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.415 ±(99.9%) 3.400 ms/op [Average]
  (min, avg, max) = (5.287, 5.415, 5.628), stdev = 0.186
  CI (99.9%): [2.014, 8.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 18.122 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.438 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.728 ±(99.9%) 0.007 ms/op
Iteration   1: 5.899 ±(99.9%) 0.012 ms/op
Iteration   2: 5.518 ±(99.9%) 0.010 ms/op
Iteration   3: 5.395 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.604 ±(99.9%) 4.788 ms/op [Average]
  (min, avg, max) = (5.395, 5.604, 5.899), stdev = 0.262
  CI (99.9%): [0.816, 10.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.284 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 8.851 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.998 ±(99.9%) 0.014 ms/op
Iteration   1: 6.510 ±(99.9%) 0.016 ms/op
Iteration   2: 6.622 ±(99.9%) 0.013 ms/op
Iteration   3: 6.637 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.590 ±(99.9%) 1.262 ms/op [Average]
  (min, avg, max) = (6.510, 6.590, 6.637), stdev = 0.069
  CI (99.9%): [5.327, 7.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 21.023 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 8.131 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.650 ±(99.9%) 0.039 ms/op
Iteration   1: 5.727 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.496 ms/op
                 createUser·p0.95:   8.946 ms/op
                 createUser·p0.99:   13.402 ms/op
                 createUser·p0.999:  23.855 ms/op
                 createUser·p0.9999: 28.548 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   2: 5.385 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.966 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.820 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  26.172 ms/op
                 createUser·p0.9999: 30.451 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 5.729 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.348 ms/op
                 createUser·p0.99:   11.846 ms/op
                 createUser·p0.999:  30.326 ms/op
                 createUser·p0.9999: 35.548 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171147
  mean =      5.609 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 68602 
    [ 5.000,  7.500) = 88528 
    [ 7.500, 10.000) = 10163 
    [10.000, 12.500) = 2393 
    [12.500, 15.000) = 796 
    [15.000, 17.500) = 310 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     25.741 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     35.802 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.013 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.370 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.729 ±(99.9%) 0.024 ms/op
Iteration   1: 5.124 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.490 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  25.362 ms/op
                 existUser·p0.9999: 29.770 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 5.403 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.873 ms/op
                 existUser·p0.95:   8.077 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  21.615 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   3: 5.709 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   7.578 ms/op
                 existUser·p0.95:   9.175 ms/op
                 existUser·p0.99:   13.009 ms/op
                 existUser·p0.999:  28.079 ms/op
                 existUser·p0.9999: 37.775 ms/op
                 existUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177710
  mean =      5.401 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 89056 
    [ 5.000,  7.500) = 75765 
    [ 7.500, 10.000) = 9105 
    [10.000, 12.500) = 2563 
    [12.500, 15.000) = 705 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     22.582 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     37.989 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 21.177 ±(99.9%) 0.428 ms/op
# Warmup Iteration   2: 7.402 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.022 ms/op
Iteration   1: 5.560 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.273 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   7.143 ms/op
                 getUser·p0.95:   8.487 ms/op
                 getUser·p0.99:   12.419 ms/op
                 getUser·p0.999:  23.118 ms/op
                 getUser·p0.9999: 28.426 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   2: 5.648 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.626 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  24.490 ms/op
                 getUser·p0.9999: 29.830 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   3: 5.577 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   10.756 ms/op
                 getUser·p0.999:  23.221 ms/op
                 getUser·p0.9999: 30.085 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171472
  mean =      5.595 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 67488 
    [ 5.000,  7.500) = 88698 
    [ 7.500, 10.000) = 11946 
    [10.000, 12.500) = 2250 
    [12.500, 15.000) = 573 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     23.233 ms/op
     p(99.9900) =     29.781 ms/op
     p(99.9990) =     31.476 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.194 ±(99.9%) 0.392 ms/op
# Warmup Iteration   2: 8.341 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.941 ±(99.9%) 0.032 ms/op
Iteration   1: 6.611 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   12.965 ms/op
                 listUser·p0.999:  27.981 ms/op
                 listUser·p0.9999: 33.762 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   2: 6.679 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.925 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.364 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   13.533 ms/op
                 listUser·p0.999:  29.956 ms/op
                 listUser·p0.9999: 33.096 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   3: 6.825 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.966 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.861 ms/op
                 listUser·p0.999:  30.430 ms/op
                 listUser·p0.9999: 33.030 ms/op
                 listUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143132
  mean =      6.704 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 7418 
    [ 5.000,  7.500) = 109119 
    [ 7.500, 10.000) = 19976 
    [10.000, 12.500) = 4684 
    [12.500, 15.000) = 1089 
    [15.000, 17.500) = 299 
    [17.500, 20.000) = 217 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 92 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      6.275 ms/op
     p(90.0000) =      8.569 ms/op
     p(95.0000) =      9.863 ms/op
     p(99.0000) =     13.353 ms/op
     p(99.9000) =     29.552 ms/op
     p(99.9900) =     33.522 ms/op
     p(99.9990) =     36.117 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.453 ± 5.877  ops/ms
ClientPb.existUser                       thrpt       3   5.915 ± 1.539  ops/ms
ClientPb.getUser                         thrpt       3   5.568 ± 1.298  ops/ms
ClientPb.listUser                        thrpt       3   4.858 ± 4.088  ops/ms
ClientPb.createUser                       avgt       3   5.512 ± 2.985   ms/op
ClientPb.existUser                        avgt       3   5.415 ± 3.400   ms/op
ClientPb.getUser                          avgt       3   5.604 ± 4.788   ms/op
ClientPb.listUser                         avgt       3   6.590 ± 1.262   ms/op
ClientPb.createUser                     sample  171147   5.609 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.966           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.372           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.210           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  177710   5.401 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.930           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.225           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.567           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.487           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.142           ms/op
ClientPb.getUser                        sample  171472   5.595 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.009           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.233           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.781           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  143132   6.704 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.505           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.275           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.863           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.353           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.522           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.569           ms/op
