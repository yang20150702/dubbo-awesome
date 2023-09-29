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
# Warmup Iteration   1: 1.073 ops/ms
# Warmup Iteration   2: 2.245 ops/ms
# Warmup Iteration   3: 5.468 ops/ms
Iteration   1: 5.971 ops/ms
Iteration   2: 5.777 ops/ms
Iteration   3: 6.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.994 ±(99.9%) 4.179 ops/ms [Average]
  (min, avg, max) = (5.777, 5.994, 6.233), stdev = 0.229
  CI (99.9%): [1.815, 10.172] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.853 ops/ms
# Warmup Iteration   2: 5.489 ops/ms
# Warmup Iteration   3: 6.058 ops/ms
Iteration   1: 6.391 ops/ms
Iteration   2: 6.187 ops/ms
Iteration   3: 6.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.204 ±(99.9%) 3.266 ops/ms [Average]
  (min, avg, max) = (6.035, 6.204, 6.391), stdev = 0.179
  CI (99.9%): [2.938, 9.471] (assumes normal distribution)


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
# Warmup Iteration   1: 1.493 ops/ms
# Warmup Iteration   2: 4.216 ops/ms
# Warmup Iteration   3: 5.848 ops/ms
Iteration   1: 5.817 ops/ms
Iteration   2: 5.813 ops/ms
Iteration   3: 5.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.782 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (5.715, 5.782, 5.817), stdev = 0.058
  CI (99.9%): [4.723, 6.841] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.638 ops/ms
# Warmup Iteration   2: 4.409 ops/ms
# Warmup Iteration   3: 5.063 ops/ms
Iteration   1: 5.169 ops/ms
Iteration   2: 5.288 ops/ms
Iteration   3: 5.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.219 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (5.169, 5.219, 5.288), stdev = 0.062
  CI (99.9%): [4.088, 6.350] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 16.361 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.262 ±(99.9%) 0.015 ms/op
Iteration   1: 5.268 ±(99.9%) 0.011 ms/op
Iteration   2: 5.314 ±(99.9%) 0.009 ms/op
Iteration   3: 5.428 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.336 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (5.268, 5.336, 5.428), stdev = 0.082
  CI (99.9%): [3.835, 6.838] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.299 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.222 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.139 ±(99.9%) 0.008 ms/op
Iteration   1: 4.893 ±(99.9%) 0.009 ms/op
Iteration   2: 4.608 ±(99.9%) 0.017 ms/op
Iteration   3: 4.766 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.756 ±(99.9%) 2.609 ms/op [Average]
  (min, avg, max) = (4.608, 4.756, 4.893), stdev = 0.143
  CI (99.9%): [2.146, 7.365] (assumes normal distribution)


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
# Warmup Iteration   1: 14.784 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.329 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.008 ms/op
Iteration   1: 4.975 ±(99.9%) 0.007 ms/op
Iteration   2: 4.901 ±(99.9%) 0.010 ms/op
Iteration   3: 4.757 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.878 ±(99.9%) 2.017 ms/op [Average]
  (min, avg, max) = (4.757, 4.878, 4.975), stdev = 0.111
  CI (99.9%): [2.861, 6.894] (assumes normal distribution)


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
# Warmup Iteration   1: 19.407 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.573 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.734 ±(99.9%) 0.009 ms/op
Iteration   1: 6.570 ±(99.9%) 0.015 ms/op
Iteration   2: 6.354 ±(99.9%) 0.012 ms/op
Iteration   3: 6.010 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.311 ±(99.9%) 5.152 ms/op [Average]
  (min, avg, max) = (6.010, 6.311, 6.570), stdev = 0.282
  CI (99.9%): [1.160, 11.463] (assumes normal distribution)


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
# Warmup Iteration   1: 16.241 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 6.225 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.024 ms/op
Iteration   1: 5.054 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.159 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   8.705 ms/op
                 createUser·p0.999:  26.530 ms/op
                 createUser·p0.9999: 33.412 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   2: 4.950 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   6.011 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  19.592 ms/op
                 createUser·p0.9999: 28.117 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 5.091 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.210 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  27.446 ms/op
                 createUser·p0.9999: 29.651 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190807
  mean =      5.031 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 120458 
    [ 5.000,  7.500) = 64849 
    [ 7.500, 10.000) = 4274 
    [10.000, 12.500) = 714 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     29.554 ms/op
     p(99.9990) =     33.936 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 16.731 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 5.838 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.261 ±(99.9%) 0.018 ms/op
Iteration   1: 5.183 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.985 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   7.406 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  23.165 ms/op
                 existUser·p0.9999: 25.580 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 4.850 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.373 ms/op
                 existUser·p0.99:   8.962 ms/op
                 existUser·p0.999:  14.370 ms/op
                 existUser·p0.9999: 28.674 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 5.157 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.274 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  27.265 ms/op
                 existUser·p0.9999: 32.080 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189606
  mean =      5.058 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 116344 
    [ 5.000,  7.500) = 65949 
    [ 7.500, 10.000) = 5801 
    [10.000, 12.500) = 845 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     23.186 ms/op
     p(99.9900) =     31.558 ms/op
     p(99.9990) =     33.017 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 18.420 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 6.771 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.170 ±(99.9%) 0.018 ms/op
Iteration   1: 5.061 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   7.004 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  23.021 ms/op
                 getUser·p0.9999: 26.497 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 5.031 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.005 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   5.956 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   10.682 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 5.021 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.454 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   5.988 ms/op
                 getUser·p0.95:   6.830 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  27.370 ms/op
                 getUser·p0.9999: 34.251 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 190473
  mean =      5.037 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 118855 
    [ 5.000,  7.500) = 64753 
    [ 7.500, 10.000) = 5173 
    [10.000, 12.500) = 1079 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.005 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.988 ms/op
     p(99.0000) =      9.687 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     33.291 ms/op
     p(99.9990) =     35.233 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 16.702 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 7.210 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.388 ±(99.9%) 0.025 ms/op
Iteration   1: 6.270 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  25.846 ms/op
                 listUser·p0.9999: 29.043 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 6.575 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   8.339 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   13.780 ms/op
                 listUser·p0.999:  27.964 ms/op
                 listUser·p0.9999: 31.054 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   3: 6.257 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  22.675 ms/op
                 listUser·p0.9999: 26.570 ms/op
                 listUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150802
  mean =      6.364 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 7733 
    [ 5.000,  7.500) = 125085 
    [ 7.500, 10.000) = 13004 
    [10.000, 12.500) = 3482 
    [12.500, 15.000) = 658 
    [15.000, 17.500) = 301 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      5.964 ms/op
     p(90.0000) =      7.772 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     29.934 ms/op
     p(99.9990) =     32.265 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.994 ± 4.179  ops/ms
ClientPb.existUser                       thrpt       3   6.204 ± 3.266  ops/ms
ClientPb.getUser                         thrpt       3   5.782 ± 1.059  ops/ms
ClientPb.listUser                        thrpt       3   5.219 ± 1.131  ops/ms
ClientPb.createUser                       avgt       3   5.336 ± 1.502   ms/op
ClientPb.existUser                        avgt       3   4.756 ± 2.609   ms/op
ClientPb.getUser                          avgt       3   4.878 ± 2.017   ms/op
ClientPb.listUser                         avgt       3   6.311 ± 5.152   ms/op
ClientPb.createUser                     sample  190807   5.031 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.177           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.060           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.952           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.554           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  189606   5.058 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.152           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.062           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.186           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.558           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  190473   5.037 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.005           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.687           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.291           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.241           ms/op
ClientPb.listUser                       sample  150802   6.364 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.772           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.756           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.934           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.997           ms/op
