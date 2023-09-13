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
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 5.727 ops/ms
# Warmup Iteration   3: 8.485 ops/ms
Iteration   1: 9.046 ops/ms
Iteration   2: 8.732 ops/ms
Iteration   3: 9.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.962 ±(99.9%) 3.667 ops/ms [Average]
  (min, avg, max) = (8.732, 8.962, 9.107), stdev = 0.201
  CI (99.9%): [5.294, 12.629] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.004 ops/ms
# Warmup Iteration   2: 8.782 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.560 ops/ms
Iteration   2: 9.380 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.561 ±(99.9%) 3.313 ops/ms [Average]
  (min, avg, max) = (9.380, 9.561, 9.743), stdev = 0.182
  CI (99.9%): [6.248, 12.874] (assumes normal distribution)


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
# Warmup Iteration   1: 2.976 ops/ms
# Warmup Iteration   2: 8.449 ops/ms
# Warmup Iteration   3: 8.820 ops/ms
Iteration   1: 9.035 ops/ms
Iteration   2: 9.219 ops/ms
Iteration   3: 8.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.035 ±(99.9%) 3.343 ops/ms [Average]
  (min, avg, max) = (8.853, 9.035, 9.219), stdev = 0.183
  CI (99.9%): [5.692, 12.379] (assumes normal distribution)


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
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 7.262 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.946 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (7.921, 7.946, 7.983), stdev = 0.032
  CI (99.9%): [7.359, 8.534] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.488 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.414 ±(99.9%) 0.014 ms/op
Iteration   2: 3.501 ±(99.9%) 0.007 ms/op
Iteration   3: 3.435 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.414, 3.450, 3.501), stdev = 0.045
  CI (99.9%): [2.629, 4.271] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.857 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.006 ms/op
Iteration   1: 3.389 ±(99.9%) 0.003 ms/op
Iteration   2: 3.438 ±(99.9%) 0.005 ms/op
Iteration   3: 3.372 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.400 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.372, 3.400, 3.438), stdev = 0.034
  CI (99.9%): [2.778, 4.021] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.587 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.006 ms/op
Iteration   1: 3.537 ±(99.9%) 0.004 ms/op
Iteration   2: 3.579 ±(99.9%) 0.006 ms/op
Iteration   3: 3.458 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.525 ±(99.9%) 1.118 ms/op [Average]
  (min, avg, max) = (3.458, 3.525, 3.579), stdev = 0.061
  CI (99.9%): [2.407, 4.642] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.990 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.378 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.008 ms/op
Iteration   1: 4.134 ±(99.9%) 0.007 ms/op
Iteration   2: 4.061 ±(99.9%) 0.009 ms/op
Iteration   3: 4.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.106 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (4.061, 4.106, 4.134), stdev = 0.039
  CI (99.9%): [3.390, 4.821] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.167 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.010 ms/op
Iteration   1: 3.550 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   7.255 ms/op
                 createUser·p0.999:  17.868 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.366 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   6.371 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 24.078 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  18.319 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275500
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9273 
    [ 2.500,  5.000) = 258352 
    [ 5.000,  7.500) = 5836 
    [ 7.500, 10.000) = 1389 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     18.694 ms/op
     p(99.9900) =     24.063 ms/op
     p(99.9990) =     25.960 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.881 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  11.945 ms/op
                 existUser·p0.9999: 24.845 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.390 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.302 ms/op
                 existUser·p0.999:  23.032 ms/op
                 existUser·p0.9999: 29.084 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   3: 3.354 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  20.466 ms/op
                 existUser·p0.9999: 41.350 ms/op
                 existUser·p1.00:   43.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283552
  mean =      3.384 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 275720 
    [ 5.000, 10.000) = 7478 
    [10.000, 15.000) = 97 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 139 
    [25.000, 30.000) = 61 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     12.357 ms/op
     p(99.9900) =     40.281 ms/op
     p(99.9990) =     43.647 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.766 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.680 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  22.207 ms/op
                 getUser·p0.9999: 25.030 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.471 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.364 ms/op
                 getUser·p0.999:  22.832 ms/op
                 getUser·p0.9999: 26.437 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270582
  mean =      3.549 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9491 
    [ 2.500,  5.000) = 251597 
    [ 5.000,  7.500) = 7607 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 148 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     25.754 ms/op
     p(99.9990) =     26.810 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.434 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.016 ms/op
Iteration   1: 4.075 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 27.956 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.130 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  15.345 ms/op
                 listUser·p0.9999: 24.224 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 4.049 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.930 ms/op
                 listUser·p0.9999: 20.881 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234799
  mean =      4.084 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 225217 
    [ 5.000,  7.500) = 6838 
    [ 7.500, 10.000) = 1923 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     27.477 ms/op
     p(99.9990) =     28.235 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.962 ± 3.667  ops/ms
ClientPb.existUser                       thrpt       3   9.561 ± 3.313  ops/ms
ClientPb.getUser                         thrpt       3   9.035 ± 3.343  ops/ms
ClientPb.listUser                        thrpt       3   7.946 ± 0.587  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 0.821   ms/op
ClientPb.existUser                        avgt       3   3.400 ± 0.621   ms/op
ClientPb.getUser                          avgt       3   3.525 ± 1.118   ms/op
ClientPb.listUser                         avgt       3   4.106 ± 0.715   ms/op
ClientPb.createUser                     sample  275500   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.366           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.694           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.063           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.345           ms/op
ClientPb.existUser                      sample  283552   3.384 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.357           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.281           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.909           ms/op
ClientPb.getUser                        sample  270582   3.549 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.071           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.414           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.754           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  234799   4.084 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.848           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.477           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
