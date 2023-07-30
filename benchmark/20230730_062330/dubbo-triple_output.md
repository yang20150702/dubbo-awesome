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
# Warmup Iteration   1: 1.407 ops/ms
# Warmup Iteration   2: 3.609 ops/ms
# Warmup Iteration   3: 6.501 ops/ms
Iteration   1: 6.135 ops/ms
Iteration   2: 6.804 ops/ms
Iteration   3: 6.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.566 ±(99.9%) 6.816 ops/ms [Average]
  (min, avg, max) = (6.135, 6.566, 6.804), stdev = 0.374
  CI (99.9%): [≈ 0, 13.382] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.147 ops/ms
# Warmup Iteration   2: 6.239 ops/ms
# Warmup Iteration   3: 6.897 ops/ms
Iteration   1: 7.267 ops/ms
Iteration   2: 7.243 ops/ms
Iteration   3: 7.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.314 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (7.243, 7.314, 7.432), stdev = 0.103
  CI (99.9%): [5.440, 9.187] (assumes normal distribution)


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
# Warmup Iteration   1: 2.036 ops/ms
# Warmup Iteration   2: 6.080 ops/ms
# Warmup Iteration   3: 6.491 ops/ms
Iteration   1: 6.788 ops/ms
Iteration   2: 6.785 ops/ms
Iteration   3: 7.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.871 ±(99.9%) 2.657 ops/ms [Average]
  (min, avg, max) = (6.785, 6.871, 7.039), stdev = 0.146
  CI (99.9%): [4.213, 9.528] (assumes normal distribution)


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
# Warmup Iteration   1: 1.826 ops/ms
# Warmup Iteration   2: 4.984 ops/ms
# Warmup Iteration   3: 5.714 ops/ms
Iteration   1: 5.692 ops/ms
Iteration   2: 5.607 ops/ms
Iteration   3: 5.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.665 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (5.607, 5.665, 5.696), stdev = 0.050
  CI (99.9%): [4.750, 6.580] (assumes normal distribution)


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
# Warmup Iteration   1: 15.711 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.900 ±(99.9%) 0.011 ms/op
Iteration   1: 4.788 ±(99.9%) 0.010 ms/op
Iteration   2: 4.835 ±(99.9%) 0.007 ms/op
Iteration   3: 4.722 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.782 ±(99.9%) 1.038 ms/op [Average]
  (min, avg, max) = (4.722, 4.782, 4.835), stdev = 0.057
  CI (99.9%): [3.744, 5.819] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.198 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.011 ms/op
Iteration   1: 4.528 ±(99.9%) 0.013 ms/op
Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
Iteration   3: 4.644 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.506 ±(99.9%) 2.751 ms/op [Average]
  (min, avg, max) = (4.345, 4.506, 4.644), stdev = 0.151
  CI (99.9%): [1.754, 7.257] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.179 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.132 ±(99.9%) 0.009 ms/op
Iteration   1: 5.139 ±(99.9%) 0.006 ms/op
Iteration   2: 4.982 ±(99.9%) 0.008 ms/op
Iteration   3: 5.059 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.060 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (4.982, 5.060, 5.139), stdev = 0.079
  CI (99.9%): [3.622, 6.498] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.812 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.168 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.851 ±(99.9%) 0.017 ms/op
Iteration   1: 5.466 ±(99.9%) 0.016 ms/op
Iteration   2: 5.599 ±(99.9%) 0.013 ms/op
Iteration   3: 5.317 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.460 ±(99.9%) 2.577 ms/op [Average]
  (min, avg, max) = (5.317, 5.460, 5.599), stdev = 0.141
  CI (99.9%): [2.883, 8.038] (assumes normal distribution)


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
# Warmup Iteration   1: 14.365 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 6.036 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.093 ±(99.9%) 0.022 ms/op
Iteration   1: 4.765 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.980 ms/op
                 createUser·p0.95:   6.717 ms/op
                 createUser·p0.99:   8.865 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 30.503 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 4.667 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.191 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.554 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  22.181 ms/op
                 createUser·p0.9999: 26.847 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 4.679 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.134 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   5.670 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  27.012 ms/op
                 createUser·p0.9999: 30.502 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 203963
  mean =      4.703 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 152237 
    [ 5.000,  7.500) = 46543 
    [ 7.500, 10.000) = 3864 
    [10.000, 12.500) = 728 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     22.775 ms/op
     p(99.9900) =     30.134 ms/op
     p(99.9990) =     32.315 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 13.692 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.165 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.947 ±(99.9%) 0.017 ms/op
Iteration   1: 4.663 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  18.317 ms/op
                 existUser·p0.9999: 23.827 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 4.730 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.792 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   9.159 ms/op
                 existUser·p0.999:  19.235 ms/op
                 existUser·p0.9999: 25.436 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 4.705 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.054 ms/op
                 existUser·p0.50:   4.481 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.472 ms/op
                 existUser·p0.99:   8.831 ms/op
                 existUser·p0.999:  18.285 ms/op
                 existUser·p0.9999: 31.883 ms/op
                 existUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 204212
  mean =      4.699 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 123 
    [ 2.500,  5.000) = 155604 
    [ 5.000,  7.500) = 43076 
    [ 7.500, 10.000) = 4006 
    [10.000, 12.500) = 877 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.562 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     31.195 ms/op
     p(99.9990) =     32.499 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.823 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.876 ±(99.9%) 0.016 ms/op
Iteration   1: 4.964 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   9.765 ms/op
                 getUser·p0.999:  22.988 ms/op
                 getUser·p0.9999: 28.890 ms/op
                 getUser·p1.00:   31.392 ms/op

Iteration   2: 4.855 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.603 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  19.561 ms/op
                 getUser·p0.9999: 26.116 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 4.713 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.956 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  14.535 ms/op
                 getUser·p0.9999: 25.924 ms/op
                 getUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 198157
  mean =      4.842 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 139701 
    [ 5.000,  7.500) = 52454 
    [ 7.500, 10.000) = 4661 
    [10.000, 12.500) = 774 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.956 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     22.572 ms/op
     p(99.9900) =     27.302 ms/op
     p(99.9990) =     29.430 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 16.971 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.419 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.945 ±(99.9%) 0.022 ms/op
Iteration   1: 5.585 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  20.701 ms/op
                 listUser·p0.9999: 23.143 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 5.495 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.859 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.569 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  21.817 ms/op
                 listUser·p0.9999: 24.096 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 5.588 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  21.162 ms/op
                 listUser·p0.9999: 25.048 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 172661
  mean =      5.556 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 54835 
    [ 5.000,  7.500) = 108315 
    [ 7.500, 10.000) = 7467 
    [10.000, 12.500) = 1218 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     21.179 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.923 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.566 ± 6.816  ops/ms
ClientPb.existUser                       thrpt       3   7.314 ± 1.873  ops/ms
ClientPb.getUser                         thrpt       3   6.871 ± 2.657  ops/ms
ClientPb.listUser                        thrpt       3   5.665 ± 0.915  ops/ms
ClientPb.createUser                       avgt       3   4.782 ± 1.038   ms/op
ClientPb.existUser                        avgt       3   4.506 ± 2.751   ms/op
ClientPb.getUser                          avgt       3   5.060 ± 1.438   ms/op
ClientPb.listUser                         avgt       3   5.460 ± 2.577   ms/op
ClientPb.createUser                     sample  203963   4.703 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.118           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.880           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.775           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  204212   4.699 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.516           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.562           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.175           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.317           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.195           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  198157   4.842 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.956           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.191           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.572           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.392           ms/op
ClientPb.listUser                       sample  172661   5.556 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.289           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.179           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.019           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.018           ms/op
