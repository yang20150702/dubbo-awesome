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
# Warmup Iteration   1: 1.290 ops/ms
# Warmup Iteration   2: 2.749 ops/ms
# Warmup Iteration   3: 5.266 ops/ms
Iteration   1: 5.653 ops/ms
Iteration   2: 5.930 ops/ms
Iteration   3: 6.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.923 ±(99.9%) 4.869 ops/ms [Average]
  (min, avg, max) = (5.653, 5.923, 6.187), stdev = 0.267
  CI (99.9%): [1.054, 10.793] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.508 ops/ms
# Warmup Iteration   2: 4.606 ops/ms
# Warmup Iteration   3: 5.772 ops/ms
Iteration   1: 6.248 ops/ms
Iteration   2: 6.509 ops/ms
Iteration   3: 6.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.362 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (6.248, 6.362, 6.509), stdev = 0.133
  CI (99.9%): [3.929, 8.795] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.759 ops/ms
# Warmup Iteration   2: 4.882 ops/ms
# Warmup Iteration   3: 5.882 ops/ms
Iteration   1: 5.826 ops/ms
Iteration   2: 6.028 ops/ms
Iteration   3: 6.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.005 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (5.826, 6.005, 6.162), stdev = 0.169
  CI (99.9%): [2.926, 9.085] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.627 ops/ms
# Warmup Iteration   2: 4.179 ops/ms
# Warmup Iteration   3: 5.120 ops/ms
Iteration   1: 5.071 ops/ms
Iteration   2: 5.129 ops/ms
Iteration   3: 5.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.180 ±(99.9%) 2.596 ops/ms [Average]
  (min, avg, max) = (5.071, 5.180, 5.341), stdev = 0.142
  CI (99.9%): [2.584, 7.777] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.971 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.788 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.277 ±(99.9%) 0.010 ms/op
Iteration   1: 5.127 ±(99.9%) 0.015 ms/op
Iteration   2: 4.962 ±(99.9%) 0.021 ms/op
Iteration   3: 5.196 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.095 ±(99.9%) 2.191 ms/op [Average]
  (min, avg, max) = (4.962, 5.095, 5.196), stdev = 0.120
  CI (99.9%): [2.904, 7.286] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.402 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.750 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.006 ms/op
Iteration   1: 4.400 ±(99.9%) 0.008 ms/op
Iteration   2: 4.193 ±(99.9%) 0.017 ms/op
Iteration   3: 4.318 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.304 ±(99.9%) 1.909 ms/op [Average]
  (min, avg, max) = (4.193, 4.304, 4.400), stdev = 0.105
  CI (99.9%): [2.395, 6.213] (assumes normal distribution)


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
# Warmup Iteration   1: 12.541 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.835 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.012 ms/op
Iteration   1: 4.636 ±(99.9%) 0.011 ms/op
Iteration   2: 4.425 ±(99.9%) 0.010 ms/op
Iteration   3: 4.485 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.515 ±(99.9%) 1.984 ms/op [Average]
  (min, avg, max) = (4.425, 4.515, 4.636), stdev = 0.109
  CI (99.9%): [2.531, 6.499] (assumes normal distribution)


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
# Warmup Iteration   1: 13.315 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.562 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.013 ms/op
Iteration   1: 4.977 ±(99.9%) 0.014 ms/op
Iteration   2: 5.071 ±(99.9%) 0.021 ms/op
Iteration   3: 5.030 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.026 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (4.977, 5.026, 5.071), stdev = 0.047
  CI (99.9%): [4.167, 5.885] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.644 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.198 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.017 ms/op
Iteration   1: 4.648 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  15.692 ms/op
                 createUser·p0.9999: 25.018 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 4.430 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  23.056 ms/op
                 createUser·p0.9999: 40.763 ms/op
                 createUser·p1.00:   40.960 ms/op

Iteration   3: 4.343 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  16.379 ms/op
                 createUser·p0.9999: 30.156 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 214613
  mean =      4.470 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 172769 
    [ 5.000, 10.000) = 41150 
    [10.000, 15.000) = 419 
    [15.000, 20.000) = 57 
    [20.000, 25.000) = 114 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.740 ms/op
     p(99.9000) =     20.525 ms/op
     p(99.9900) =     38.601 ms/op
     p(99.9990) =     40.885 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.620 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.014 ms/op
Iteration   1: 4.404 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  16.370 ms/op
                 existUser·p0.9999: 24.067 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 4.230 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.890 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 4.349 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.003 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   8.028 ms/op
                 existUser·p0.999:  12.393 ms/op
                 existUser·p0.9999: 25.557 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 221883
  mean =      4.326 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 122 
    [ 2.500,  5.000) = 195791 
    [ 5.000,  7.500) = 23292 
    [ 7.500, 10.000) = 1951 
    [10.000, 12.500) = 455 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     24.826 ms/op
     p(99.9990) =     26.780 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.832 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.221 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.015 ms/op
Iteration   1: 4.444 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 4.331 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   6.250 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  24.401 ms/op
                 getUser·p0.9999: 28.791 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   3: 4.378 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.874 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  15.345 ms/op
                 getUser·p0.9999: 27.204 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 218773
  mean =      4.384 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 188543 
    [ 5.000,  7.500) = 26472 
    [ 7.500, 10.000) = 2727 
    [10.000, 12.500) = 585 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      4.170 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     22.920 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     29.086 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 12.723 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.602 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.265 ±(99.9%) 0.017 ms/op
Iteration   1: 5.083 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  24.776 ms/op
                 listUser·p0.9999: 29.220 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 5.221 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   9.718 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 24.820 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 5.508 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   3.129 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  18.280 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 182128
  mean =      5.265 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 88811 
    [ 5.000,  7.500) = 86287 
    [ 7.500, 10.000) = 5343 
    [10.000, 12.500) = 1034 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     30.039 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.923 ± 4.869  ops/ms
ClientPb.existUser                       thrpt       3   6.362 ± 2.433  ops/ms
ClientPb.getUser                         thrpt       3   6.005 ± 3.079  ops/ms
ClientPb.listUser                        thrpt       3   5.180 ± 2.596  ops/ms
ClientPb.createUser                       avgt       3   5.095 ± 2.191   ms/op
ClientPb.existUser                        avgt       3   4.304 ± 1.909   ms/op
ClientPb.getUser                          avgt       3   4.515 ± 1.984   ms/op
ClientPb.listUser                         avgt       3   5.026 ± 0.859   ms/op
ClientPb.createUser                     sample  214613   4.470 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.468           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.740           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.525           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.601           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.960           ms/op
ClientPb.existUser                      sample  221883   4.326 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.823           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.826           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.656           ms/op
ClientPb.getUser                        sample  218773   4.384 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.315           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.920           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.638           ms/op
ClientPb.listUser                       sample  182128   5.265 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.208           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.792           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.951           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.147           ms/op
