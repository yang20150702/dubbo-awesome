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
# Warmup Iteration   1: 1.009 ops/ms
# Warmup Iteration   2: 2.293 ops/ms
# Warmup Iteration   3: 5.131 ops/ms
Iteration   1: 5.469 ops/ms
Iteration   2: 5.626 ops/ms
Iteration   3: 5.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.585 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (5.469, 5.585, 5.659), stdev = 0.102
  CI (99.9%): [3.731, 7.439] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 4.455 ops/ms
# Warmup Iteration   3: 5.708 ops/ms
Iteration   1: 5.795 ops/ms
Iteration   2: 6.180 ops/ms
Iteration   3: 6.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.080 ±(99.9%) 4.578 ops/ms [Average]
  (min, avg, max) = (5.795, 6.080, 6.266), stdev = 0.251
  CI (99.9%): [1.502, 10.658] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.512 ops/ms
# Warmup Iteration   2: 4.413 ops/ms
# Warmup Iteration   3: 5.615 ops/ms
Iteration   1: 5.635 ops/ms
Iteration   2: 5.579 ops/ms
Iteration   3: 5.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.578 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (5.521, 5.578, 5.635), stdev = 0.057
  CI (99.9%): [4.539, 6.618] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 3.663 ops/ms
# Warmup Iteration   3: 4.673 ops/ms
Iteration   1: 4.835 ops/ms
Iteration   2: 4.975 ops/ms
Iteration   3: 4.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.897 ±(99.9%) 1.297 ops/ms [Average]
  (min, avg, max) = (4.835, 4.897, 4.975), stdev = 0.071
  CI (99.9%): [3.601, 6.194] (assumes normal distribution)


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
# Warmup Iteration   1: 19.122 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 6.845 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.847 ±(99.9%) 0.014 ms/op
Iteration   1: 5.887 ±(99.9%) 0.010 ms/op
Iteration   2: 5.508 ±(99.9%) 0.017 ms/op
Iteration   3: 5.722 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.706 ±(99.9%) 3.472 ms/op [Average]
  (min, avg, max) = (5.508, 5.706, 5.887), stdev = 0.190
  CI (99.9%): [2.234, 9.177] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.803 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.749 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.618 ±(99.9%) 0.007 ms/op
Iteration   1: 5.491 ±(99.9%) 0.016 ms/op
Iteration   2: 5.450 ±(99.9%) 0.012 ms/op
Iteration   3: 5.375 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.439 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (5.375, 5.439, 5.491), stdev = 0.059
  CI (99.9%): [4.364, 6.514] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.901 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.672 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.906 ±(99.9%) 0.009 ms/op
Iteration   1: 5.591 ±(99.9%) 0.010 ms/op
Iteration   2: 5.650 ±(99.9%) 0.010 ms/op
Iteration   3: 5.603 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.615 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (5.591, 5.615, 5.650), stdev = 0.031
  CI (99.9%): [5.043, 6.186] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.877 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 8.148 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.674 ±(99.9%) 0.009 ms/op
Iteration   1: 6.450 ±(99.9%) 0.011 ms/op
Iteration   2: 6.367 ±(99.9%) 0.015 ms/op
Iteration   3: 6.674 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.497 ±(99.9%) 2.897 ms/op [Average]
  (min, avg, max) = (6.367, 6.497, 6.674), stdev = 0.159
  CI (99.9%): [3.600, 9.394] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.284 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 7.559 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.419 ±(99.9%) 0.033 ms/op
Iteration   1: 5.685 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  32.244 ms/op
                 createUser·p0.9999: 43.057 ms/op
                 createUser·p1.00:   43.909 ms/op

Iteration   2: 5.413 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.548 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.283 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  26.966 ms/op
                 createUser·p0.9999: 37.761 ms/op
                 createUser·p1.00:   38.076 ms/op

Iteration   3: 5.802 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.454 ms/op
                 createUser·p0.50:   5.448 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  15.052 ms/op
                 createUser·p0.9999: 30.455 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170377
  mean =      5.629 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53248 
    [ 5.000, 10.000) = 114725 
    [10.000, 15.000) = 2117 
    [15.000, 20.000) = 86 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 56 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 44 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     10.588 ms/op
     p(99.9000) =     23.951 ms/op
     p(99.9900) =     42.009 ms/op
     p(99.9990) =     43.448 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.938 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 6.499 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.508 ±(99.9%) 0.023 ms/op
Iteration   1: 5.288 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.671 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  15.598 ms/op
                 existUser·p0.9999: 26.701 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   2: 5.272 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   11.052 ms/op
                 existUser·p0.999:  26.500 ms/op
                 existUser·p0.9999: 32.405 ms/op
                 existUser·p1.00:   33.292 ms/op

Iteration   3: 5.411 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.725 ms/op
                 existUser·p0.99:   10.174 ms/op
                 existUser·p0.999:  28.998 ms/op
                 existUser·p0.9999: 33.184 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180151
  mean =      5.323 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 89046 
    [ 5.000,  7.500) = 81123 
    [ 7.500, 10.000) = 7730 
    [10.000, 12.500) = 1451 
    [12.500, 15.000) = 495 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     16.737 ms/op
     p(99.9900) =     32.570 ms/op
     p(99.9990) =     33.725 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.009 ±(99.9%) 0.355 ms/op
# Warmup Iteration   2: 6.821 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.601 ±(99.9%) 0.021 ms/op
Iteration   1: 5.801 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.005 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.668 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.321 ms/op
                 getUser·p0.999:  28.636 ms/op
                 getUser·p0.9999: 33.176 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   2: 5.457 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.750 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  19.425 ms/op
                 getUser·p0.9999: 31.162 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   3: 5.388 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.799 ms/op
                 getUser·p0.99:   10.666 ms/op
                 getUser·p0.999:  27.547 ms/op
                 getUser·p0.9999: 35.394 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173054
  mean =      5.543 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 70139 
    [ 5.000,  7.500) = 90302 
    [ 7.500, 10.000) = 9573 
    [10.000, 12.500) = 2059 
    [12.500, 15.000) = 520 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.604 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 20.832 ±(99.9%) 0.408 ms/op
# Warmup Iteration   2: 8.635 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 6.852 ±(99.9%) 0.033 ms/op
Iteration   1: 6.546 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  27.798 ms/op
                 listUser·p0.9999: 30.638 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 6.354 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  29.482 ms/op
                 listUser·p0.9999: 34.729 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   3: 6.628 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.219 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  24.467 ms/op
                 listUser·p0.9999: 28.859 ms/op
                 listUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147427
  mean =      6.507 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 4827 
    [ 5.000,  7.500) = 122622 
    [ 7.500, 10.000) = 14629 
    [10.000, 12.500) = 3682 
    [12.500, 15.000) = 1022 
    [15.000, 17.500) = 302 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      6.062 ms/op
     p(90.0000) =      7.946 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     12.829 ms/op
     p(99.9000) =     27.525 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     35.279 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.585 ± 1.854  ops/ms
ClientPb.existUser                       thrpt       3   6.080 ± 4.578  ops/ms
ClientPb.getUser                         thrpt       3   5.578 ± 1.039  ops/ms
ClientPb.listUser                        thrpt       3   4.897 ± 1.297  ops/ms
ClientPb.createUser                       avgt       3   5.706 ± 3.472   ms/op
ClientPb.existUser                        avgt       3   5.439 ± 1.075   ms/op
ClientPb.getUser                          avgt       3   5.615 ± 0.572   ms/op
ClientPb.listUser                         avgt       3   6.497 ± 2.897   ms/op
ClientPb.createUser                     sample  170377   5.629 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.118           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.588           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.951           ms/op
ClientPb.createUser:createUser·p0.9999  sample          42.009           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.909           ms/op
ClientPb.existUser                      sample  180151   5.323 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.676           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.737           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.570           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  173054   5.543 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.653           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.930           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.298           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.961           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.513           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.144           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  147427   6.507 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.062           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.946           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.388           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.829           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.525           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.882           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
