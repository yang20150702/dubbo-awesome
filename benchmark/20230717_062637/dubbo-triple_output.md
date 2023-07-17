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
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 4.263 ops/ms
# Warmup Iteration   3: 6.965 ops/ms
Iteration   1: 6.802 ops/ms
Iteration   2: 7.488 ops/ms
Iteration   3: 7.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.364 ±(99.9%) 9.321 ops/ms [Average]
  (min, avg, max) = (6.802, 7.364, 7.801), stdev = 0.511
  CI (99.9%): [≈ 0, 16.685] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.365 ops/ms
# Warmup Iteration   2: 6.993 ops/ms
# Warmup Iteration   3: 7.681 ops/ms
Iteration   1: 8.024 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.057 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (8.024, 8.057, 8.077), stdev = 0.029
  CI (99.9%): [7.532, 8.583] (assumes normal distribution)


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
# Warmup Iteration   1: 1.513 ops/ms
# Warmup Iteration   2: 3.001 ops/ms
# Warmup Iteration   3: 7.426 ops/ms
Iteration   1: 7.521 ops/ms
Iteration   2: 7.122 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.479 ±(99.9%) 6.151 ops/ms [Average]
  (min, avg, max) = (7.122, 7.479, 7.792), stdev = 0.337
  CI (99.9%): [1.327, 13.630] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.964 ops/ms
# Warmup Iteration   2: 5.381 ops/ms
# Warmup Iteration   3: 6.281 ops/ms
Iteration   1: 6.360 ops/ms
Iteration   2: 6.638 ops/ms
Iteration   3: 6.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.611 ±(99.9%) 4.337 ops/ms [Average]
  (min, avg, max) = (6.360, 6.611, 6.833), stdev = 0.238
  CI (99.9%): [2.274, 10.947] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.569 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.005 ms/op
Iteration   1: 4.201 ±(99.9%) 0.008 ms/op
Iteration   2: 4.331 ±(99.9%) 0.005 ms/op
Iteration   3: 4.364 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.299 ±(99.9%) 1.581 ms/op [Average]
  (min, avg, max) = (4.201, 4.299, 4.364), stdev = 0.087
  CI (99.9%): [2.717, 5.880] (assumes normal distribution)


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
# Warmup Iteration   1: 13.761 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.006 ms/op
Iteration   1: 4.097 ±(99.9%) 0.005 ms/op
Iteration   2: 3.941 ±(99.9%) 0.007 ms/op
Iteration   3: 3.790 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.943 ±(99.9%) 2.794 ms/op [Average]
  (min, avg, max) = (3.790, 3.943, 4.097), stdev = 0.153
  CI (99.9%): [1.149, 6.736] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.855 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.238 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.595 ±(99.9%) 0.010 ms/op
Iteration   1: 4.494 ±(99.9%) 0.014 ms/op
Iteration   2: 4.866 ±(99.9%) 0.007 ms/op
Iteration   3: 5.020 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.793 ±(99.9%) 4.929 ms/op [Average]
  (min, avg, max) = (4.494, 4.793, 5.020), stdev = 0.270
  CI (99.9%): [≈ 0, 9.722] (assumes normal distribution)


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
# Warmup Iteration   1: 16.390 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.437 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.783 ±(99.9%) 0.014 ms/op
Iteration   1: 5.205 ±(99.9%) 0.009 ms/op
Iteration   2: 4.881 ±(99.9%) 0.011 ms/op
Iteration   3: 5.014 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.033 ±(99.9%) 2.969 ms/op [Average]
  (min, avg, max) = (4.881, 5.033, 5.205), stdev = 0.163
  CI (99.9%): [2.065, 8.002] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.030 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.966 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.022 ms/op
Iteration   1: 4.138 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  10.531 ms/op
                 createUser·p0.9999: 25.357 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 4.454 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.909 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   6.365 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  29.548 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   35.652 ms/op

Iteration   3: 4.332 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.382 ms/op
                 createUser·p0.99:   8.872 ms/op
                 createUser·p0.999:  15.109 ms/op
                 createUser·p0.9999: 32.072 ms/op
                 createUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 222858
  mean =      4.304 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227 
    [ 2.500,  5.000) = 190230 
    [ 5.000,  7.500) = 28833 
    [ 7.500, 10.000) = 2384 
    [10.000, 12.500) = 754 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     22.226 ms/op
     p(99.9900) =     33.545 ms/op
     p(99.9990) =     35.296 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 14.395 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.018 ms/op
Iteration   1: 4.182 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   6.034 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  12.969 ms/op
                 existUser·p0.9999: 31.960 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   6.014 ms/op
                 existUser·p0.99:   8.251 ms/op
                 existUser·p0.999:  15.214 ms/op
                 existUser·p0.9999: 28.737 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   3: 4.491 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.759 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 31.326 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 222677
  mean =      4.309 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 191854 
    [ 5.000,  7.500) = 26055 
    [ 7.500, 10.000) = 3448 
    [10.000, 12.500) = 644 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     18.885 ms/op
     p(99.9900) =     31.291 ms/op
     p(99.9990) =     32.254 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 14.420 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.468 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.016 ms/op
Iteration   1: 4.275 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   9.339 ms/op
                 getUser·p0.999:  22.571 ms/op
                 getUser·p0.9999: 26.398 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 4.324 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   6.439 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  17.498 ms/op
                 getUser·p0.9999: 27.745 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   3: 4.404 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   6.454 ms/op
                 getUser·p0.99:   9.634 ms/op
                 getUser·p0.999:  15.455 ms/op
                 getUser·p0.9999: 37.141 ms/op
                 getUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 221431
  mean =      4.334 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 191774 
    [ 5.000,  7.500) = 24346 
    [ 7.500, 10.000) = 3646 
    [10.000, 12.500) = 1073 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     35.118 ms/op
     p(99.9990) =     38.179 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


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
# Warmup Iteration   1: 17.090 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.706 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.580 ±(99.9%) 0.028 ms/op
Iteration   1: 5.644 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   5.095 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   11.452 ms/op
                 listUser·p0.999:  30.476 ms/op
                 listUser·p0.9999: 35.499 ms/op
                 listUser·p1.00:   38.142 ms/op

Iteration   2: 5.204 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  26.607 ms/op
                 listUser·p0.9999: 30.554 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 5.440 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  18.985 ms/op
                 listUser·p0.9999: 23.670 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 176967
  mean =      5.423 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 93832 
    [ 5.000,  7.500) = 71105 
    [ 7.500, 10.000) = 9838 
    [10.000, 12.500) = 1490 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     26.183 ms/op
     p(99.9900) =     33.864 ms/op
     p(99.9990) =     36.427 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.364 ± 9.321  ops/ms
ClientPb.existUser                       thrpt       3   8.057 ± 0.526  ops/ms
ClientPb.getUser                         thrpt       3   7.479 ± 6.151  ops/ms
ClientPb.listUser                        thrpt       3   6.611 ± 4.337  ops/ms
ClientPb.createUser                       avgt       3   4.299 ± 1.581   ms/op
ClientPb.existUser                        avgt       3   3.943 ± 2.794   ms/op
ClientPb.getUser                          avgt       3   4.793 ± 4.929   ms/op
ClientPb.listUser                         avgt       3   5.033 ± 2.969   ms/op
ClientPb.createUser                     sample  222858   4.304 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.411           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.226           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.545           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.652           ms/op
ClientPb.existUser                      sample  222677   4.309 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.700           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.885           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.291           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  221431   4.334 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.159           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.940           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.118           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.732           ms/op
ClientPb.listUser                       sample  176967   5.423 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.995           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.420           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.183           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.864           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.142           ms/op
