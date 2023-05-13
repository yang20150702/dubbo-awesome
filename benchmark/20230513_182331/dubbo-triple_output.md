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
# Warmup Iteration   1: 1.133 ops/ms
# Warmup Iteration   2: 2.690 ops/ms
# Warmup Iteration   3: 5.073 ops/ms
Iteration   1: 5.635 ops/ms
Iteration   2: 5.620 ops/ms
Iteration   3: 5.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.692 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (5.620, 5.692, 5.822), stdev = 0.113
  CI (99.9%): [3.633, 7.751] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.850 ops/ms
# Warmup Iteration   2: 5.149 ops/ms
# Warmup Iteration   3: 6.034 ops/ms
Iteration   1: 5.761 ops/ms
Iteration   2: 6.084 ops/ms
Iteration   3: 6.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.025 ±(99.9%) 4.379 ops/ms [Average]
  (min, avg, max) = (5.761, 6.025, 6.230), stdev = 0.240
  CI (99.9%): [1.646, 10.404] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.578 ops/ms
# Warmup Iteration   2: 4.927 ops/ms
# Warmup Iteration   3: 5.359 ops/ms
Iteration   1: 5.531 ops/ms
Iteration   2: 5.797 ops/ms
Iteration   3: 5.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.605 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (5.487, 5.605, 5.797), stdev = 0.167
  CI (99.9%): [2.550, 8.660] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.544 ops/ms
# Warmup Iteration   2: 4.055 ops/ms
# Warmup Iteration   3: 4.879 ops/ms
Iteration   1: 4.827 ops/ms
Iteration   2: 4.906 ops/ms
Iteration   3: 4.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.811 ±(99.9%) 1.889 ops/ms [Average]
  (min, avg, max) = (4.701, 4.811, 4.906), stdev = 0.104
  CI (99.9%): [2.922, 6.700] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.778 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.492 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.915 ±(99.9%) 0.010 ms/op
Iteration   1: 5.783 ±(99.9%) 0.007 ms/op
Iteration   2: 5.439 ±(99.9%) 0.012 ms/op
Iteration   3: 5.338 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.520 ±(99.9%) 4.253 ms/op [Average]
  (min, avg, max) = (5.338, 5.520, 5.783), stdev = 0.233
  CI (99.9%): [1.267, 9.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.015 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.094 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.270 ±(99.9%) 0.013 ms/op
Iteration   1: 5.205 ±(99.9%) 0.011 ms/op
Iteration   2: 5.165 ±(99.9%) 0.011 ms/op
Iteration   3: 5.115 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.162 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (5.115, 5.162, 5.205), stdev = 0.045
  CI (99.9%): [4.344, 5.980] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.472 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.495 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.009 ms/op
Iteration   1: 5.654 ±(99.9%) 0.010 ms/op
Iteration   2: 5.862 ±(99.9%) 0.010 ms/op
Iteration   3: 5.625 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.714 ±(99.9%) 2.363 ms/op [Average]
  (min, avg, max) = (5.625, 5.714, 5.862), stdev = 0.129
  CI (99.9%): [3.351, 8.076] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.757 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.949 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.876 ±(99.9%) 0.017 ms/op
Iteration   1: 6.641 ±(99.9%) 0.014 ms/op
Iteration   2: 6.739 ±(99.9%) 0.006 ms/op
Iteration   3: 6.628 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.669 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (6.628, 6.669, 6.739), stdev = 0.061
  CI (99.9%): [5.560, 7.778] (assumes normal distribution)


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
# Warmup Iteration   1: 16.572 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.823 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.965 ±(99.9%) 0.028 ms/op
Iteration   1: 5.885 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.751 ms/op
                 createUser·p0.90:   7.463 ms/op
                 createUser·p0.95:   8.307 ms/op
                 createUser·p0.99:   11.190 ms/op
                 createUser·p0.999:  25.309 ms/op
                 createUser·p0.9999: 33.123 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   2: 5.811 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.258 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  15.466 ms/op
                 createUser·p0.9999: 40.730 ms/op
                 createUser·p1.00:   41.878 ms/op

Iteration   3: 5.667 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.176 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  28.364 ms/op
                 createUser·p0.9999: 31.404 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165731
  mean =      5.786 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 50131 
    [ 5.000, 10.000) = 113270 
    [10.000, 15.000) = 2040 
    [15.000, 20.000) = 110 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 62 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     21.752 ms/op
     p(99.9900) =     37.203 ms/op
     p(99.9990) =     41.791 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 16.971 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.726 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.643 ±(99.9%) 0.021 ms/op
Iteration   1: 5.821 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.831 ms/op
                 existUser·p0.50:   5.677 ms/op
                 existUser·p0.90:   7.471 ms/op
                 existUser·p0.95:   8.241 ms/op
                 existUser·p0.99:   10.355 ms/op
                 existUser·p0.999:  15.302 ms/op
                 existUser·p0.9999: 27.115 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   2: 5.613 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   5.571 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   7.840 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  27.788 ms/op
                 existUser·p0.9999: 31.399 ms/op
                 existUser·p1.00:   32.997 ms/op

Iteration   3: 5.555 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.078 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  27.473 ms/op
                 existUser·p0.9999: 30.776 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169575
  mean =      5.661 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 59638 
    [ 5.000,  7.500) = 96367 
    [ 7.500, 10.000) = 11593 
    [10.000, 12.500) = 1261 
    [12.500, 15.000) = 408 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     18.728 ms/op
     p(99.9900) =     31.005 ms/op
     p(99.9990) =     33.057 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.608 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 7.054 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.809 ±(99.9%) 0.021 ms/op
Iteration   1: 5.640 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.208 ms/op
                 getUser·p0.99:   11.108 ms/op
                 getUser·p0.999:  15.435 ms/op
                 getUser·p0.9999: 27.045 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   2: 5.726 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.617 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   7.692 ms/op
                 getUser·p0.99:   10.863 ms/op
                 getUser·p0.999:  25.108 ms/op
                 getUser·p0.9999: 31.372 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   3: 5.996 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.875 ms/op
                 getUser·p0.50:   5.743 ms/op
                 getUser·p0.90:   7.717 ms/op
                 getUser·p0.95:   8.405 ms/op
                 getUser·p0.99:   10.568 ms/op
                 getUser·p0.999:  27.296 ms/op
                 getUser·p0.9999: 33.162 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165828
  mean =      5.784 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 50917 
    [ 5.000,  7.500) = 100381 
    [ 7.500, 10.000) = 11899 
    [10.000, 12.500) = 1912 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      7.332 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.841 ms/op
     p(99.9000) =     18.537 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     33.623 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 18.381 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 7.877 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 7.069 ±(99.9%) 0.035 ms/op
Iteration   1: 6.932 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   6.636 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  29.548 ms/op
                 listUser·p0.9999: 33.094 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 6.616 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.445 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  28.563 ms/op
                 listUser·p0.9999: 32.965 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   3: 6.445 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  27.663 ms/op
                 listUser·p0.9999: 34.409 ms/op
                 listUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144042
  mean =      6.658 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 7029 
    [ 5.000,  7.500) = 111984 
    [ 7.500, 10.000) = 21161 
    [10.000, 12.500) = 2705 
    [12.500, 15.000) = 768 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.052 ms/op
     p(50.0000) =      6.423 ms/op
     p(90.0000) =      8.167 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     28.703 ms/op
     p(99.9900) =     32.997 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.692 ± 2.059  ops/ms
ClientPb.existUser                       thrpt       3   6.025 ± 4.379  ops/ms
ClientPb.getUser                         thrpt       3   5.605 ± 3.055  ops/ms
ClientPb.listUser                        thrpt       3   4.811 ± 1.889  ops/ms
ClientPb.createUser                       avgt       3   5.520 ± 4.253   ms/op
ClientPb.existUser                        avgt       3   5.162 ± 0.818   ms/op
ClientPb.getUser                          avgt       3   5.714 ± 2.363   ms/op
ClientPb.listUser                         avgt       3   6.669 ± 1.109   ms/op
ClientPb.createUser                     sample  165731   5.786 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.454           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.291           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.020           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.752           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.203           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.878           ms/op
ClientPb.existUser                      sample  169575   5.661 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.642           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.201           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.045           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.289           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.728           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.005           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.194           ms/op
ClientPb.getUser                        sample  165828   5.784 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.184           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.841           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.537           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  144042   6.658 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.052           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.423           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.703           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.997           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.472           ms/op
