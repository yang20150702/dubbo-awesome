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
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 3.895 ops/ms
# Warmup Iteration   3: 7.346 ops/ms
Iteration   1: 7.769 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.107 ±(99.9%) 5.686 ops/ms [Average]
  (min, avg, max) = (7.769, 8.107, 8.382), stdev = 0.312
  CI (99.9%): [2.422, 13.793] (assumes normal distribution)


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
# Warmup Iteration   1: 2.569 ops/ms
# Warmup Iteration   2: 7.791 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.810 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.564 ±(99.9%) 6.630 ops/ms [Average]
  (min, avg, max) = (8.147, 8.564, 8.810), stdev = 0.363
  CI (99.9%): [1.935, 15.194] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.053 ops/ms
# Warmup Iteration   2: 5.944 ops/ms
# Warmup Iteration   3: 7.975 ops/ms
Iteration   1: 7.968 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 8.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.178 ±(99.9%) 3.314 ops/ms [Average]
  (min, avg, max) = (7.968, 8.178, 8.289), stdev = 0.182
  CI (99.9%): [4.864, 11.492] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 5.818 ops/ms
# Warmup Iteration   3: 6.836 ops/ms
Iteration   1: 6.834 ops/ms
Iteration   2: 6.775 ops/ms
Iteration   3: 6.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.817 ±(99.9%) 0.669 ops/ms [Average]
  (min, avg, max) = (6.775, 6.817, 6.842), stdev = 0.037
  CI (99.9%): [6.148, 7.486] (assumes normal distribution)


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
# Warmup Iteration   1: 11.272 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.010 ms/op
Iteration   1: 3.759 ±(99.9%) 0.009 ms/op
Iteration   2: 3.863 ±(99.9%) 0.008 ms/op
Iteration   3: 3.845 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.822 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.759, 3.822, 3.863), stdev = 0.055
  CI (99.9%): [2.814, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 11.044 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.003 ms/op
Iteration   1: 3.834 ±(99.9%) 0.006 ms/op
Iteration   2: 3.785 ±(99.9%) 0.010 ms/op
Iteration   3: 3.557 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.725 ±(99.9%) 2.698 ms/op [Average]
  (min, avg, max) = (3.557, 3.725, 3.834), stdev = 0.148
  CI (99.9%): [1.027, 6.423] (assumes normal distribution)


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
# Warmup Iteration   1: 14.217 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.003 ms/op
Iteration   1: 3.945 ±(99.9%) 0.004 ms/op
Iteration   2: 4.029 ±(99.9%) 0.008 ms/op
Iteration   3: 3.883 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.952 ±(99.9%) 1.340 ms/op [Average]
  (min, avg, max) = (3.883, 3.952, 4.029), stdev = 0.073
  CI (99.9%): [2.612, 5.292] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.693 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.327 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.567 ±(99.9%) 0.012 ms/op
Iteration   1: 4.491 ±(99.9%) 0.012 ms/op
Iteration   2: 4.491 ±(99.9%) 0.014 ms/op
Iteration   3: 4.544 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.508 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (4.491, 4.508, 4.544), stdev = 0.031
  CI (99.9%): [3.948, 5.069] (assumes normal distribution)


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
# Warmup Iteration   1: 11.899 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.017 ms/op
Iteration   1: 3.842 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 32.188 ms/op
                 createUser·p1.00:   33.292 ms/op

Iteration   2: 4.041 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.785 ms/op
                 createUser·p0.999:  25.657 ms/op
                 createUser·p0.9999: 29.920 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.093 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  27.332 ms/op
                 createUser·p0.9999: 31.130 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244424
  mean =      3.928 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 598 
    [ 2.500,  5.000) = 231639 
    [ 5.000,  7.500) = 10669 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     25.349 ms/op
     p(99.9900) =     31.228 ms/op
     p(99.9990) =     33.121 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.510 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.012 ms/op
Iteration   1: 3.967 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  23.996 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   2: 3.757 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  16.937 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.717 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  28.043 ms/op
                 existUser·p0.9999: 32.078 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251927
  mean =      3.811 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 753 
    [ 2.500,  5.000) = 241780 
    [ 5.000,  7.500) = 7551 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     22.816 ms/op
     p(99.9900) =     29.976 ms/op
     p(99.9990) =     32.881 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 12.124 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.016 ms/op
Iteration   1: 3.979 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  19.693 ms/op
                 getUser·p0.9999: 24.540 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  11.213 ms/op
                 getUser·p0.9999: 26.271 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  25.807 ms/op
                 getUser·p0.9999: 30.113 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245238
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 634 
    [ 2.500,  5.000) = 233551 
    [ 5.000,  7.500) = 9519 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.759 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     19.456 ms/op
     p(99.9900) =     28.131 ms/op
     p(99.9990) =     30.656 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 14.295 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.050 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.862 ±(99.9%) 0.024 ms/op
Iteration   1: 4.627 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  24.740 ms/op
                 listUser·p0.9999: 32.425 ms/op
                 listUser·p1.00:   33.423 ms/op

Iteration   2: 4.452 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 21.970 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 4.539 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  18.401 ms/op
                 listUser·p0.9999: 24.404 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211252
  mean =      4.538 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 191760 
    [ 5.000,  7.500) = 15370 
    [ 7.500, 10.000) = 2869 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     20.095 ms/op
     p(99.9900) =     31.617 ms/op
     p(99.9990) =     33.343 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.107 ± 5.686  ops/ms
ClientPb.existUser                       thrpt       3   8.564 ± 6.630  ops/ms
ClientPb.getUser                         thrpt       3   8.178 ± 3.314  ops/ms
ClientPb.listUser                        thrpt       3   6.817 ± 0.669  ops/ms
ClientPb.createUser                       avgt       3   3.822 ± 1.008   ms/op
ClientPb.existUser                        avgt       3   3.725 ± 2.698   ms/op
ClientPb.getUser                          avgt       3   3.952 ± 1.340   ms/op
ClientPb.listUser                         avgt       3   4.508 ± 0.561   ms/op
ClientPb.createUser                     sample  244424   3.928 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.395           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.228           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  251927   3.811 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.413           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.816           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  245238   3.916 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.759           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.456           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.131           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  211252   4.538 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.095           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.617           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.423           ms/op
