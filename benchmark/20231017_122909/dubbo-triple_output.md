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
# Warmup Iteration   1: 2.131 ops/ms
# Warmup Iteration   2: 5.685 ops/ms
# Warmup Iteration   3: 8.028 ops/ms
Iteration   1: 8.734 ops/ms
Iteration   2: 8.905 ops/ms
Iteration   3: 8.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.797 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (8.734, 8.797, 8.905), stdev = 0.094
  CI (99.9%): [7.080, 10.514] (assumes normal distribution)


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
# Warmup Iteration   1: 2.653 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 9.310 ops/ms
Iteration   1: 9.211 ops/ms
Iteration   2: 9.147 ops/ms
Iteration   3: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.175 ±(99.9%) 0.599 ops/ms [Average]
  (min, avg, max) = (9.147, 9.175, 9.211), stdev = 0.033
  CI (99.9%): [8.577, 9.774] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.728 ops/ms
# Warmup Iteration   2: 8.308 ops/ms
# Warmup Iteration   3: 8.818 ops/ms
Iteration   1: 8.584 ops/ms
Iteration   2: 8.940 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.762 ±(99.9%) 3.249 ops/ms [Average]
  (min, avg, max) = (8.584, 8.762, 8.940), stdev = 0.178
  CI (99.9%): [5.513, 12.011] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.921 ops/ms
# Warmup Iteration   2: 7.103 ops/ms
# Warmup Iteration   3: 7.588 ops/ms
Iteration   1: 7.627 ops/ms
Iteration   2: 7.449 ops/ms
Iteration   3: 7.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.549 ±(99.9%) 1.660 ops/ms [Average]
  (min, avg, max) = (7.449, 7.549, 7.627), stdev = 0.091
  CI (99.9%): [5.889, 9.209] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.797 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.005 ms/op
Iteration   1: 3.551 ±(99.9%) 0.005 ms/op
Iteration   2: 3.597 ±(99.9%) 0.003 ms/op
Iteration   3: 3.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.564 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.546, 3.564, 3.597), stdev = 0.028
  CI (99.9%): [3.052, 4.077] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.505 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.004 ms/op
Iteration   1: 3.440 ±(99.9%) 0.004 ms/op
Iteration   2: 3.403 ±(99.9%) 0.005 ms/op
Iteration   3: 3.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.466 ±(99.9%) 1.469 ms/op [Average]
  (min, avg, max) = (3.403, 3.466, 3.557), stdev = 0.081
  CI (99.9%): [1.998, 4.935] (assumes normal distribution)


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
# Warmup Iteration   1: 9.725 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.006 ms/op
Iteration   1: 3.524 ±(99.9%) 0.005 ms/op
Iteration   2: 3.539 ±(99.9%) 0.005 ms/op
Iteration   3: 3.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.524, 3.540, 3.558), stdev = 0.017
  CI (99.9%): [3.231, 3.849] (assumes normal distribution)


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
# Warmup Iteration   1: 11.465 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.006 ms/op
Iteration   1: 4.248 ±(99.9%) 0.007 ms/op
Iteration   2: 4.237 ±(99.9%) 0.008 ms/op
Iteration   3: 4.306 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.264 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (4.237, 4.264, 4.306), stdev = 0.037
  CI (99.9%): [3.589, 4.938] (assumes normal distribution)


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
# Warmup Iteration   1: 11.943 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.015 ms/op
Iteration   1: 3.576 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 24.250 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.623 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  22.291 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.564 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.788 ms/op
                 createUser·p0.999:  21.943 ms/op
                 createUser·p0.9999: 31.064 ms/op
                 createUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267517
  mean =      3.588 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5283 
    [ 2.500,  5.000) = 253335 
    [ 5.000,  7.500) = 6713 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     21.446 ms/op
     p(99.9900) =     29.204 ms/op
     p(99.9990) =     31.282 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 9.436 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
Iteration   1: 3.594 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  22.610 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  23.703 ms/op
                 existUser·p0.9999: 27.569 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   7.442 ms/op
                 existUser·p0.999:  13.360 ms/op
                 existUser·p0.9999: 29.413 ms/op
                 existUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274223
  mean =      3.501 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5581 
    [ 2.500,  5.000) = 258312 
    [ 5.000,  7.500) = 8289 
    [ 7.500, 10.000) = 1503 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.494 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 12.263 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.014 ms/op
Iteration   1: 3.743 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   8.742 ms/op
                 getUser·p0.999:  22.712 ms/op
                 getUser·p0.9999: 25.654 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.598 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.445 ms/op
                 getUser·p0.999:  13.355 ms/op
                 getUser·p0.9999: 26.218 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.650 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  25.042 ms/op
                 getUser·p0.9999: 29.114 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 261984
  mean =      3.663 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3004 
    [ 2.500,  5.000) = 246505 
    [ 5.000,  7.500) = 8610 
    [ 7.500, 10.000) = 2815 
    [10.000, 12.500) = 584 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 110 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     21.268 ms/op
     p(99.9900) =     28.521 ms/op
     p(99.9990) =     29.831 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 13.257 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.475 ±(99.9%) 0.016 ms/op
Iteration   1: 4.282 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  21.551 ms/op
                 listUser·p0.9999: 25.070 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   2: 4.317 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  18.165 ms/op
                 listUser·p0.9999: 21.789 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.340 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 18.774 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222469
  mean =      4.313 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 208041 
    [ 5.000,  7.500) = 9575 
    [ 7.500, 10.000) = 3328 
    [10.000, 12.500) = 739 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     27.317 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.797 ± 1.717  ops/ms
ClientPb.existUser                       thrpt       3   9.175 ± 0.599  ops/ms
ClientPb.getUser                         thrpt       3   8.762 ± 3.249  ops/ms
ClientPb.listUser                        thrpt       3   7.549 ± 1.660  ops/ms
ClientPb.createUser                       avgt       3   3.564 ± 0.512   ms/op
ClientPb.existUser                        avgt       3   3.466 ± 1.469   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 0.309   ms/op
ClientPb.listUser                         avgt       3   4.264 ± 0.674   ms/op
ClientPb.createUser                     sample  267517   3.588 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.496           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.446           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.204           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.359           ms/op
ClientPb.existUser                      sample  274223   3.501 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.464           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.344           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  261984   3.663 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.787           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.954           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.521           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  222469   4.313 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.286           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.252           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.888           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.689           ms/op
