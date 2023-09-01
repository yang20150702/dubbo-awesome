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
# Warmup Iteration   1: 1.112 ops/ms
# Warmup Iteration   2: 2.471 ops/ms
# Warmup Iteration   3: 4.736 ops/ms
Iteration   1: 5.573 ops/ms
Iteration   2: 5.833 ops/ms
Iteration   3: 5.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.748 ±(99.9%) 2.765 ops/ms [Average]
  (min, avg, max) = (5.573, 5.748, 5.837), stdev = 0.152
  CI (99.9%): [2.982, 8.513] (assumes normal distribution)


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
# Warmup Iteration   1: 1.626 ops/ms
# Warmup Iteration   2: 4.696 ops/ms
# Warmup Iteration   3: 5.953 ops/ms
Iteration   1: 6.090 ops/ms
Iteration   2: 6.130 ops/ms
Iteration   3: 6.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.106 ±(99.9%) 0.382 ops/ms [Average]
  (min, avg, max) = (6.090, 6.106, 6.130), stdev = 0.021
  CI (99.9%): [5.724, 6.488] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.696 ops/ms
# Warmup Iteration   2: 4.603 ops/ms
# Warmup Iteration   3: 5.513 ops/ms
Iteration   1: 5.728 ops/ms
Iteration   2: 5.726 ops/ms
Iteration   3: 5.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.692 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (5.624, 5.692, 5.728), stdev = 0.060
  CI (99.9%): [4.605, 6.780] (assumes normal distribution)


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
# Warmup Iteration   1: 1.548 ops/ms
# Warmup Iteration   2: 3.767 ops/ms
# Warmup Iteration   3: 5.035 ops/ms
Iteration   1: 4.813 ops/ms
Iteration   2: 4.940 ops/ms
Iteration   3: 5.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.927 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (4.813, 4.927, 5.029), stdev = 0.108
  CI (99.9%): [2.954, 6.901] (assumes normal distribution)


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
# Warmup Iteration   1: 17.791 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.892 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.670 ±(99.9%) 0.011 ms/op
Iteration   1: 5.442 ±(99.9%) 0.011 ms/op
Iteration   2: 5.644 ±(99.9%) 0.007 ms/op
Iteration   3: 5.512 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.532 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (5.442, 5.532, 5.644), stdev = 0.102
  CI (99.9%): [3.664, 7.400] (assumes normal distribution)


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
# Warmup Iteration   1: 17.882 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.425 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.359 ±(99.9%) 0.011 ms/op
Iteration   1: 5.230 ±(99.9%) 0.015 ms/op
Iteration   2: 5.276 ±(99.9%) 0.010 ms/op
Iteration   3: 5.287 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.264 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (5.230, 5.264, 5.287), stdev = 0.030
  CI (99.9%): [4.711, 5.817] (assumes normal distribution)


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
# Warmup Iteration   1: 17.820 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.173 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.748 ±(99.9%) 0.010 ms/op
Iteration   1: 5.663 ±(99.9%) 0.011 ms/op
Iteration   2: 5.570 ±(99.9%) 0.007 ms/op
Iteration   3: 5.515 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.583 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (5.515, 5.583, 5.663), stdev = 0.075
  CI (99.9%): [4.218, 6.947] (assumes normal distribution)


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
# Warmup Iteration   1: 19.029 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.317 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.395 ±(99.9%) 0.016 ms/op
Iteration   1: 6.565 ±(99.9%) 0.011 ms/op
Iteration   2: 6.396 ±(99.9%) 0.013 ms/op
Iteration   3: 6.131 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.364 ±(99.9%) 3.988 ms/op [Average]
  (min, avg, max) = (6.131, 6.364, 6.565), stdev = 0.219
  CI (99.9%): [2.377, 10.352] (assumes normal distribution)


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
# Warmup Iteration   1: 18.148 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 7.391 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.932 ±(99.9%) 0.027 ms/op
Iteration   1: 5.544 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.478 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   8.184 ms/op
                 createUser·p0.99:   11.583 ms/op
                 createUser·p0.999:  24.462 ms/op
                 createUser·p0.9999: 29.393 ms/op
                 createUser·p1.00:   33.194 ms/op

Iteration   2: 5.499 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.824 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  26.379 ms/op
                 createUser·p0.9999: 30.271 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   3: 5.498 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.441 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   11.534 ms/op
                 createUser·p0.999:  26.182 ms/op
                 createUser·p0.9999: 29.923 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174068
  mean =      5.514 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 69290 
    [ 5.000,  7.500) = 93265 
    [ 7.500, 10.000) = 8280 
    [10.000, 12.500) = 1970 
    [12.500, 15.000) = 662 
    [15.000, 17.500) = 243 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     25.917 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     33.145 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 16.452 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 5.796 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.473 ±(99.9%) 0.022 ms/op
Iteration   1: 5.387 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.695 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  22.925 ms/op
                 existUser·p0.9999: 29.215 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   2: 5.400 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.791 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  19.759 ms/op
                 existUser·p0.9999: 31.235 ms/op
                 existUser·p1.00:   33.063 ms/op

Iteration   3: 5.431 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.726 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   11.444 ms/op
                 existUser·p0.999:  27.681 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177641
  mean =      5.406 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 80495 
    [ 5.000,  7.500) = 86097 
    [ 7.500, 10.000) = 8416 
    [10.000, 12.500) = 1689 
    [12.500, 15.000) = 526 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     21.540 ms/op
     p(99.9900) =     30.810 ms/op
     p(99.9990) =     33.481 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 17.672 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 7.842 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 5.815 ±(99.9%) 0.022 ms/op
Iteration   1: 5.700 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.654 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   11.313 ms/op
                 getUser·p0.999:  24.687 ms/op
                 getUser·p0.9999: 28.236 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   2: 5.635 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.531 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.939 ms/op
                 getUser·p0.95:   8.356 ms/op
                 getUser·p0.99:   12.059 ms/op
                 getUser·p0.999:  22.619 ms/op
                 getUser·p0.9999: 26.487 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 5.930 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.515 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.455 ms/op
                 getUser·p0.95:   8.995 ms/op
                 getUser·p0.99:   12.255 ms/op
                 getUser·p0.999:  26.683 ms/op
                 getUser·p0.9999: 29.794 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166718
  mean =      5.752 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 44691 
    [ 5.000,  7.500) = 108991 
    [ 7.500, 10.000) = 9046 
    [10.000, 12.500) = 2678 
    [12.500, 15.000) = 811 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.515 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     28.748 ms/op
     p(99.9990) =     29.972 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 18.267 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 8.492 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.988 ±(99.9%) 0.031 ms/op
Iteration   1: 6.655 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   13.844 ms/op
                 listUser·p0.999:  28.704 ms/op
                 listUser·p0.9999: 31.890 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 6.367 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.241 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  28.331 ms/op
                 listUser·p0.9999: 32.276 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 6.422 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.829 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  23.370 ms/op
                 listUser·p0.9999: 33.686 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148048
  mean =      6.479 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 6603 
    [ 5.000,  7.500) = 121294 
    [ 7.500, 10.000) = 14252 
    [10.000, 12.500) = 4187 
    [12.500, 15.000) = 1087 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      6.062 ms/op
     p(90.0000) =      8.053 ms/op
     p(95.0000) =      9.552 ms/op
     p(99.0000) =     12.878 ms/op
     p(99.9000) =     27.524 ms/op
     p(99.9900) =     33.075 ms/op
     p(99.9990) =     34.705 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.748 ± 2.765  ops/ms
ClientPb.existUser                       thrpt       3   6.106 ± 0.382  ops/ms
ClientPb.getUser                         thrpt       3   5.692 ± 1.088  ops/ms
ClientPb.listUser                        thrpt       3   4.927 ± 1.973  ops/ms
ClientPb.createUser                       avgt       3   5.532 ± 1.868   ms/op
ClientPb.existUser                        avgt       3   5.264 ± 0.553   ms/op
ClientPb.getUser                          avgt       3   5.583 ± 1.364   ms/op
ClientPb.listUser                         avgt       3   6.364 ± 3.988   ms/op
ClientPb.createUser                     sample  174068   5.514 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.441           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.020           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.485           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.917           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.884           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.194           ms/op
ClientPb.existUser                      sample  177641   5.406 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.991           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.071           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.889           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.540           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.810           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  166718   5.752 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.960           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.938           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.748           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  148048   6.479 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.973           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.062           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.878           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.524           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.075           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
