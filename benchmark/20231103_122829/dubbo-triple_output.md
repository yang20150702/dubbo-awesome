# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 4.297 ops/ms
# Warmup Iteration   3: 7.464 ops/ms
Iteration   1: 7.795 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 8.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.073 ±(99.9%) 6.350 ops/ms [Average]
  (min, avg, max) = (7.795, 8.073, 8.463), stdev = 0.348
  CI (99.9%): [1.723, 14.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.744 ops/ms
# Warmup Iteration   2: 9.038 ops/ms
# Warmup Iteration   3: 9.303 ops/ms
Iteration   1: 9.670 ops/ms
Iteration   2: 10.026 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.799 ±(99.9%) 3.602 ops/ms [Average]
  (min, avg, max) = (9.670, 9.799, 10.026), stdev = 0.197
  CI (99.9%): [6.197, 13.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.378 ops/ms
# Warmup Iteration   2: 8.804 ops/ms
# Warmup Iteration   3: 9.290 ops/ms
Iteration   1: 9.455 ops/ms
Iteration   2: 9.325 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.360 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (9.299, 9.360, 9.455), stdev = 0.083
  CI (99.9%): [7.839, 10.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.612 ops/ms
# Warmup Iteration   2: 7.050 ops/ms
# Warmup Iteration   3: 7.351 ops/ms
Iteration   1: 7.458 ops/ms
Iteration   2: 7.425 ops/ms
Iteration   3: 7.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.445 ±(99.9%) 0.321 ops/ms [Average]
  (min, avg, max) = (7.425, 7.445, 7.458), stdev = 0.018
  CI (99.9%): [7.124, 7.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.234 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.002 ms/op
Iteration   1: 3.479 ±(99.9%) 0.006 ms/op
Iteration   2: 3.428 ±(99.9%) 0.004 ms/op
Iteration   3: 3.406 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.406, 3.437, 3.479), stdev = 0.037
  CI (99.9%): [2.756, 4.119] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.192 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.006 ms/op
Iteration   1: 3.288 ±(99.9%) 0.006 ms/op
Iteration   2: 3.422 ±(99.9%) 0.004 ms/op
Iteration   3: 3.447 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.386 ±(99.9%) 1.553 ms/op [Average]
  (min, avg, max) = (3.288, 3.386, 3.447), stdev = 0.085
  CI (99.9%): [1.833, 4.939] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.109 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.003 ms/op
Iteration   1: 3.485 ±(99.9%) 0.007 ms/op
Iteration   2: 3.426 ±(99.9%) 0.005 ms/op
Iteration   3: 3.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.485 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.426, 3.485, 3.544), stdev = 0.059
  CI (99.9%): [2.406, 4.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.267 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.538 ±(99.9%) 0.005 ms/op
Iteration   1: 4.369 ±(99.9%) 0.005 ms/op
Iteration   2: 4.309 ±(99.9%) 0.007 ms/op
Iteration   3: 4.218 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.299 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (4.218, 4.299, 4.369), stdev = 0.076
  CI (99.9%): [2.916, 5.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.860 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.357 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  18.121 ms/op
                 createUser·p0.9999: 21.741 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.387 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  20.290 ms/op
                 createUser·p0.9999: 23.822 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.400 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  17.680 ms/op
                 createUser·p0.9999: 24.235 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283873
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7884 
    [ 2.500,  5.000) = 271084 
    [ 5.000,  7.500) = 3743 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     17.994 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     25.409 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.771 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
Iteration   1: 3.386 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.026 ms/op
                 existUser·p0.999:  17.450 ms/op
                 existUser·p0.9999: 20.793 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 3.459 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  18.418 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  13.279 ms/op
                 existUser·p0.9999: 26.739 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281422
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5712 
    [ 2.500,  5.000) = 269266 
    [ 5.000,  7.500) = 5252 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     26.046 ms/op
     p(99.9990) =     26.867 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.489 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.011 ms/op
Iteration   1: 3.565 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  19.209 ms/op
                 getUser·p0.9999: 21.399 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.473 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 24.569 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.446 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.328 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  19.314 ms/op
                 getUser·p0.9999: 26.378 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274902
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3367 
    [ 2.500,  5.000) = 265170 
    [ 5.000,  7.500) = 5001 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     25.412 ms/op
     p(99.9990) =     26.821 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.850 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.014 ms/op
Iteration   1: 4.202 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  21.656 ms/op
                 listUser·p0.9999: 27.649 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 4.145 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.817 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.644 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.244 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   4.157 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 23.056 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228630
  mean =      4.197 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 149 
    [ 2.500,  5.000) = 214181 
    [ 5.000,  7.500) = 12314 
    [ 7.500, 10.000) = 1148 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     16.734 ms/op
     p(99.9900) =     26.874 ms/op
     p(99.9990) =     28.260 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.073 ± 6.350  ops/ms
ClientPb.existUser                       thrpt       3   9.799 ± 3.602  ops/ms
ClientPb.getUser                         thrpt       3   9.360 ± 1.520  ops/ms
ClientPb.listUser                        thrpt       3   7.445 ± 0.321  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 0.682   ms/op
ClientPb.existUser                        avgt       3   3.386 ± 1.553   ms/op
ClientPb.getUser                          avgt       3   3.485 ± 1.079   ms/op
ClientPb.listUser                         avgt       3   4.299 ± 1.383   ms/op
ClientPb.createUser                     sample  283873   3.381 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.994           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.724           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.952           ms/op
ClientPb.existUser                      sample  281422   3.410 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.615           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.046           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  274902   3.494 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.328           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.412           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  228630   4.197 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.270           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.734           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.874           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.508           ms/op
