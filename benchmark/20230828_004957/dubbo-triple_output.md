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
# Warmup Iteration   1: 1.648 ops/ms
# Warmup Iteration   2: 3.825 ops/ms
# Warmup Iteration   3: 7.315 ops/ms
Iteration   1: 7.477 ops/ms
Iteration   2: 7.472 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.659 ±(99.9%) 5.833 ops/ms [Average]
  (min, avg, max) = (7.472, 7.659, 8.028), stdev = 0.320
  CI (99.9%): [1.826, 13.492] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.324 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.295 ops/ms
Iteration   2: 8.468 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.359 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (8.295, 8.359, 8.468), stdev = 0.096
  CI (99.9%): [6.616, 10.101] (assumes normal distribution)


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
# Warmup Iteration   1: 2.405 ops/ms
# Warmup Iteration   2: 6.905 ops/ms
# Warmup Iteration   3: 8.027 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.042 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (7.984, 8.042, 8.074), stdev = 0.050
  CI (99.9%): [7.131, 8.953] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.098 ops/ms
# Warmup Iteration   2: 5.702 ops/ms
# Warmup Iteration   3: 6.761 ops/ms
Iteration   1: 6.756 ops/ms
Iteration   2: 6.804 ops/ms
Iteration   3: 6.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.784 ±(99.9%) 0.458 ops/ms [Average]
  (min, avg, max) = (6.756, 6.784, 6.804), stdev = 0.025
  CI (99.9%): [6.326, 7.242] (assumes normal distribution)


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
# Warmup Iteration   1: 11.265 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.003 ms/op
Iteration   1: 3.992 ±(99.9%) 0.005 ms/op
Iteration   2: 3.865 ±(99.9%) 0.012 ms/op
Iteration   3: 3.924 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.927 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (3.865, 3.927, 3.992), stdev = 0.063
  CI (99.9%): [2.768, 5.085] (assumes normal distribution)


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
# Warmup Iteration   1: 10.866 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.004 ms/op
Iteration   1: 3.712 ±(99.9%) 0.007 ms/op
Iteration   2: 3.859 ±(99.9%) 0.004 ms/op
Iteration   3: 3.797 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.789 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.712, 3.789, 3.859), stdev = 0.074
  CI (99.9%): [2.446, 5.132] (assumes normal distribution)


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
# Warmup Iteration   1: 10.319 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.007 ms/op
Iteration   1: 4.271 ±(99.9%) 0.005 ms/op
Iteration   2: 4.109 ±(99.9%) 0.009 ms/op
Iteration   3: 3.924 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.101 ±(99.9%) 3.166 ms/op [Average]
  (min, avg, max) = (3.924, 4.101, 4.271), stdev = 0.174
  CI (99.9%): [0.935, 7.267] (assumes normal distribution)


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
# Warmup Iteration   1: 14.135 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.204 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.007 ms/op
Iteration   1: 4.698 ±(99.9%) 0.010 ms/op
Iteration   2: 4.583 ±(99.9%) 0.013 ms/op
Iteration   3: 4.716 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.666 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (4.583, 4.666, 4.716), stdev = 0.072
  CI (99.9%): [3.353, 5.978] (assumes normal distribution)


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
# Warmup Iteration   1: 12.631 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.016 ms/op
Iteration   1: 3.980 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  23.287 ms/op
                 createUser·p0.9999: 44.939 ms/op
                 createUser·p1.00:   46.203 ms/op

Iteration   2: 4.040 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  26.673 ms/op
                 createUser·p0.9999: 29.988 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  10.844 ms/op
                 createUser·p0.9999: 32.502 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240104
  mean =      3.997 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 226816 
    [ 5.000, 10.000) = 12480 
    [10.000, 15.000) = 532 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 105 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     23.295 ms/op
     p(99.9900) =     42.860 ms/op
     p(99.9990) =     45.967 ms/op
     p(99.9999) =     46.203 ms/op
    p(100.0000) =     46.203 ms/op


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
# Warmup Iteration   1: 12.429 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.012 ms/op
Iteration   1: 3.851 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.011 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   7.442 ms/op
                 existUser·p0.999:  23.261 ms/op
                 existUser·p0.9999: 25.516 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.830 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 27.884 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   3: 3.857 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.743 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.512 ms/op
                 existUser·p0.999:  12.436 ms/op
                 existUser·p0.9999: 28.499 ms/op
                 existUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249507
  mean =      3.846 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 392 
    [ 2.500,  5.000) = 238595 
    [ 5.000,  7.500) = 8136 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 686 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     28.084 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 11.112 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.015 ms/op
Iteration   1: 4.123 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   6.356 ms/op
                 getUser·p0.99:   9.126 ms/op
                 getUser·p0.999:  23.915 ms/op
                 getUser·p0.9999: 32.825 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.580 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 28.318 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 3.957 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   7.614 ms/op
                 getUser·p0.999:  31.603 ms/op
                 getUser·p0.9999: 34.341 ms/op
                 getUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237404
  mean =      4.042 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 223580 
    [ 5.000,  7.500) = 9497 
    [ 7.500, 10.000) = 3141 
    [10.000, 12.500) = 730 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 67 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     33.497 ms/op
     p(99.9990) =     34.726 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 13.805 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.357 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.018 ms/op
Iteration   1: 4.760 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  25.293 ms/op
                 listUser·p0.9999: 29.464 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   2: 4.773 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  20.933 ms/op
                 listUser·p0.9999: 26.388 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.689 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202347
  mean =      4.740 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 165456 
    [ 5.000,  7.500) = 29917 
    [ 7.500, 10.000) = 5371 
    [10.000, 12.500) = 1025 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     21.812 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     30.669 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.659 ± 5.833  ops/ms
ClientPb.existUser                       thrpt       3   8.359 ± 1.743  ops/ms
ClientPb.getUser                         thrpt       3   8.042 ± 0.911  ops/ms
ClientPb.listUser                        thrpt       3   6.784 ± 0.458  ops/ms
ClientPb.createUser                       avgt       3   3.927 ± 1.158   ms/op
ClientPb.existUser                        avgt       3   3.789 ± 1.343   ms/op
ClientPb.getUser                          avgt       3   4.101 ± 3.166   ms/op
ClientPb.listUser                         avgt       3   4.666 ± 1.313   ms/op
ClientPb.createUser                     sample  240104   3.997 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.692           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.295           ms/op
ClientPb.createUser:createUser·p0.9999  sample          42.860           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.203           ms/op
ClientPb.existUser                      sample  249507   3.846 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.743           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.084           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.032           ms/op
ClientPb.getUser                        sample  237404   4.042 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.370           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.888           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.497           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  202347   4.740 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.388           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.812           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.312           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.802           ms/op
