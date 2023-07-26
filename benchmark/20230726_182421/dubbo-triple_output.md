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
# Warmup Iteration   1: 1.075 ops/ms
# Warmup Iteration   2: 2.485 ops/ms
# Warmup Iteration   3: 4.461 ops/ms
Iteration   1: 5.348 ops/ms
Iteration   2: 5.676 ops/ms
Iteration   3: 5.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.652 ±(99.9%) 5.337 ops/ms [Average]
  (min, avg, max) = (5.348, 5.652, 5.932), stdev = 0.293
  CI (99.9%): [0.314, 10.989] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.702 ops/ms
# Warmup Iteration   2: 4.673 ops/ms
# Warmup Iteration   3: 5.874 ops/ms
Iteration   1: 5.927 ops/ms
Iteration   2: 6.116 ops/ms
Iteration   3: 5.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.960 ±(99.9%) 2.594 ops/ms [Average]
  (min, avg, max) = (5.838, 5.960, 6.116), stdev = 0.142
  CI (99.9%): [3.366, 8.554] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 4.254 ops/ms
# Warmup Iteration   3: 5.446 ops/ms
Iteration   1: 5.464 ops/ms
Iteration   2: 5.655 ops/ms
Iteration   3: 5.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.642 ±(99.9%) 3.121 ops/ms [Average]
  (min, avg, max) = (5.464, 5.642, 5.805), stdev = 0.171
  CI (99.9%): [2.521, 8.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.511 ops/ms
# Warmup Iteration   2: 3.655 ops/ms
# Warmup Iteration   3: 4.689 ops/ms
Iteration   1: 4.755 ops/ms
Iteration   2: 4.811 ops/ms
Iteration   3: 4.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.792 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (4.755, 4.792, 4.811), stdev = 0.032
  CI (99.9%): [4.207, 5.376] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.448 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.899 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.889 ±(99.9%) 0.009 ms/op
Iteration   1: 5.737 ±(99.9%) 0.010 ms/op
Iteration   2: 5.421 ±(99.9%) 0.014 ms/op
Iteration   3: 5.428 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.529 ±(99.9%) 3.287 ms/op [Average]
  (min, avg, max) = (5.421, 5.529, 5.737), stdev = 0.180
  CI (99.9%): [2.241, 8.816] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.444 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.195 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.023 ms/op
Iteration   1: 5.395 ±(99.9%) 0.013 ms/op
Iteration   2: 5.277 ±(99.9%) 0.015 ms/op
Iteration   3: 5.594 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.422 ±(99.9%) 2.926 ms/op [Average]
  (min, avg, max) = (5.277, 5.422, 5.594), stdev = 0.160
  CI (99.9%): [2.496, 8.349] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.282 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.961 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.631 ±(99.9%) 0.009 ms/op
Iteration   1: 5.532 ±(99.9%) 0.017 ms/op
Iteration   2: 5.886 ±(99.9%) 0.008 ms/op
Iteration   3: 5.678 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.699 ±(99.9%) 3.251 ms/op [Average]
  (min, avg, max) = (5.532, 5.699, 5.886), stdev = 0.178
  CI (99.9%): [2.448, 8.949] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 21.053 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 8.856 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.710 ±(99.9%) 0.012 ms/op
Iteration   1: 6.659 ±(99.9%) 0.021 ms/op
Iteration   2: 6.498 ±(99.9%) 0.020 ms/op
Iteration   3: 6.283 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.480 ±(99.9%) 3.434 ms/op [Average]
  (min, avg, max) = (6.283, 6.480, 6.659), stdev = 0.188
  CI (99.9%): [3.046, 9.914] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.083 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 8.076 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.994 ±(99.9%) 0.025 ms/op
Iteration   1: 5.641 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.142 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  26.749 ms/op
                 createUser·p0.9999: 33.412 ms/op
                 createUser·p1.00:   35.848 ms/op

Iteration   2: 5.865 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.540 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  17.225 ms/op
                 createUser·p0.9999: 33.343 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   3: 5.712 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   7.863 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  36.309 ms/op
                 createUser·p0.9999: 45.444 ms/op
                 createUser·p1.00:   45.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167189
  mean =      5.738 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 40126 
    [ 5.000, 10.000) = 125232 
    [10.000, 15.000) = 1559 
    [15.000, 20.000) = 106 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     19.642 ms/op
     p(99.9900) =     44.321 ms/op
     p(99.9990) =     45.853 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


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
# Warmup Iteration   1: 17.729 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 6.553 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.587 ±(99.9%) 0.021 ms/op
Iteration   1: 5.500 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   6.726 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 5.447 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  26.940 ms/op
                 existUser·p0.9999: 30.487 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   3: 5.314 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   6.881 ms/op
                 existUser·p0.99:   9.630 ms/op
                 existUser·p0.999:  27.467 ms/op
                 existUser·p0.9999: 30.996 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177058
  mean =      5.419 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 69356 
    [ 5.000,  7.500) = 100375 
    [ 7.500, 10.000) = 5373 
    [10.000, 12.500) = 1091 
    [12.500, 15.000) = 515 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     17.300 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     32.858 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 18.562 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 7.263 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.896 ±(99.9%) 0.021 ms/op
Iteration   1: 5.875 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.818 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.324 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   11.682 ms/op
                 getUser·p0.999:  17.255 ms/op
                 getUser·p0.9999: 28.731 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   2: 5.816 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.512 ms/op
                 getUser·p0.99:   10.017 ms/op
                 getUser·p0.999:  25.756 ms/op
                 getUser·p0.9999: 31.621 ms/op
                 getUser·p1.00:   31.916 ms/op

Iteration   3: 5.868 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.605 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.348 ms/op
                 getUser·p0.99:   11.583 ms/op
                 getUser·p0.999:  27.877 ms/op
                 getUser·p0.9999: 31.584 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163835
  mean =      5.853 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 34623 
    [ 5.000,  7.500) = 117196 
    [ 7.500, 10.000) = 9004 
    [10.000, 12.500) = 2077 
    [12.500, 15.000) = 439 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     21.048 ms/op
     p(99.9900) =     31.125 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 22.193 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 8.336 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.666 ±(99.9%) 0.025 ms/op
Iteration   1: 6.647 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.068 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  26.342 ms/op
                 listUser·p0.9999: 38.101 ms/op
                 listUser·p1.00:   38.601 ms/op

Iteration   2: 6.706 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  28.836 ms/op
                 listUser·p0.9999: 35.062 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   3: 6.511 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.035 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   11.801 ms/op
                 listUser·p0.999:  22.905 ms/op
                 listUser·p0.9999: 41.490 ms/op
                 listUser·p1.00:   41.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144817
  mean =      6.620 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3039 
    [ 5.000, 10.000) = 137859 
    [10.000, 15.000) = 3409 
    [15.000, 20.000) = 225 
    [20.000, 25.000) = 108 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 58 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      6.341 ms/op
     p(90.0000) =      7.758 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     26.363 ms/op
     p(99.9900) =     37.882 ms/op
     p(99.9990) =     41.767 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.652 ± 5.337  ops/ms
ClientPb.existUser                       thrpt       3   5.960 ± 2.594  ops/ms
ClientPb.getUser                         thrpt       3   5.642 ± 3.121  ops/ms
ClientPb.listUser                        thrpt       3   4.792 ± 0.584  ops/ms
ClientPb.createUser                       avgt       3   5.529 ± 3.287   ms/op
ClientPb.existUser                        avgt       3   5.422 ± 2.926   ms/op
ClientPb.getUser                          avgt       3   5.699 ± 3.251   ms/op
ClientPb.listUser                         avgt       3   6.480 ± 3.434   ms/op
ClientPb.createUser                     sample  167189   5.738 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.782           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.142           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.642           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.321           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.941           ms/op
ClientPb.existUser                      sample  177058   5.419 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.300           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.671           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  163835   5.853 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.261           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.272           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.048           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.125           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768           ms/op
ClientPb.listUser                       sample  144817   6.620 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.367           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.341           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.534           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.363           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.882           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.943           ms/op
