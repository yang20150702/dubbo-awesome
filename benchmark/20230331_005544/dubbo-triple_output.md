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
# Warmup Iteration   1: 1.806 ops/ms
# Warmup Iteration   2: 4.285 ops/ms
# Warmup Iteration   3: 7.420 ops/ms
Iteration   1: 7.492 ops/ms
Iteration   2: 7.726 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.787 ±(99.9%) 6.012 ops/ms [Average]
  (min, avg, max) = (7.492, 7.787, 8.143), stdev = 0.330
  CI (99.9%): [1.775, 13.799] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.778 ops/ms
# Warmup Iteration   2: 7.299 ops/ms
# Warmup Iteration   3: 8.369 ops/ms
Iteration   1: 8.675 ops/ms
Iteration   2: 8.387 ops/ms
Iteration   3: 8.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.502 ±(99.9%) 2.779 ops/ms [Average]
  (min, avg, max) = (8.387, 8.502, 8.675), stdev = 0.152
  CI (99.9%): [5.723, 11.281] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 6.497 ops/ms
# Warmup Iteration   3: 7.727 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.607 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.858 ±(99.9%) 6.183 ops/ms [Average]
  (min, avg, max) = (7.607, 7.858, 8.243), stdev = 0.339
  CI (99.9%): [1.675, 14.040] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 5.319 ops/ms
# Warmup Iteration   3: 6.352 ops/ms
Iteration   1: 6.691 ops/ms
Iteration   2: 6.911 ops/ms
Iteration   3: 6.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.767 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (6.691, 6.767, 6.911), stdev = 0.125
  CI (99.9%): [4.489, 9.045] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.585 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
Iteration   2: 4.084 ±(99.9%) 0.005 ms/op
Iteration   3: 4.056 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.005 ±(99.9%) 2.060 ms/op [Average]
  (min, avg, max) = (3.876, 4.005, 4.084), stdev = 0.113
  CI (99.9%): [1.946, 6.065] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.890 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.005 ms/op
Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
Iteration   2: 3.789 ±(99.9%) 0.007 ms/op
Iteration   3: 3.844 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.800 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.768, 3.800, 3.844), stdev = 0.039
  CI (99.9%): [3.083, 4.517] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.849 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.042 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.011 ms/op
Iteration   1: 4.041 ±(99.9%) 0.008 ms/op
Iteration   2: 4.000 ±(99.9%) 0.009 ms/op
Iteration   3: 3.990 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.010 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.990, 4.010, 4.041), stdev = 0.027
  CI (99.9%): [3.522, 4.499] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.683 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.348 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.014 ms/op
Iteration   1: 4.671 ±(99.9%) 0.014 ms/op
Iteration   2: 4.694 ±(99.9%) 0.011 ms/op
Iteration   3: 4.663 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.676 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (4.663, 4.676, 4.694), stdev = 0.016
  CI (99.9%): [4.386, 4.966] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.434 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 5.523 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.519 ±(99.9%) 0.018 ms/op
Iteration   1: 4.227 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  14.915 ms/op
                 createUser·p0.9999: 25.647 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 26.149 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.823 ms/op
                 createUser·p0.999:  21.420 ms/op
                 createUser·p0.9999: 29.231 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234993
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 492 
    [ 2.500,  5.000) = 219748 
    [ 5.000,  7.500) = 12234 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     27.869 ms/op
     p(99.9990) =     29.381 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 11.953 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.012 ms/op
Iteration   1: 3.811 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.102 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  14.320 ms/op
                 existUser·p0.9999: 25.304 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.971 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  25.345 ms/op
                 existUser·p0.9999: 34.406 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   3: 3.928 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  9.722 ms/op
                 existUser·p0.9999: 31.125 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246000
  mean =      3.902 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 204 
    [ 2.500,  5.000) = 230557 
    [ 5.000,  7.500) = 13238 
    [ 7.500, 10.000) = 1302 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     33.207 ms/op
     p(99.9990) =     34.901 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 12.424 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.014 ms/op
Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  24.522 ms/op
                 getUser·p0.9999: 25.669 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 4.093 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.892 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  10.216 ms/op
                 getUser·p0.9999: 28.132 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.953 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.604 ms/op
                 getUser·p0.999:  14.619 ms/op
                 getUser·p0.9999: 31.064 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235423
  mean =      4.076 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 217977 
    [ 5.000,  7.500) = 15111 
    [ 7.500, 10.000) = 1562 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     23.598 ms/op
     p(99.9900) =     29.965 ms/op
     p(99.9990) =     32.093 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 15.407 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.586 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.018 ms/op
Iteration   1: 4.598 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  25.280 ms/op
                 listUser·p0.9999: 29.196 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   2: 4.714 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 20.585 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 4.963 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   9.466 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 20.793 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201861
  mean =      4.754 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 168682 
    [ 5.000,  7.500) = 27084 
    [ 7.500, 10.000) = 4845 
    [10.000, 12.500) = 726 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.878 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     28.195 ms/op
     p(99.9990) =     30.305 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.787 ± 6.012  ops/ms
ClientPb.existUser                       thrpt       3   8.502 ± 2.779  ops/ms
ClientPb.getUser                         thrpt       3   7.858 ± 6.183  ops/ms
ClientPb.listUser                        thrpt       3   6.767 ± 2.278  ops/ms
ClientPb.createUser                       avgt       3   4.005 ± 2.060   ms/op
ClientPb.existUser                        avgt       3   3.800 ± 0.717   ms/op
ClientPb.getUser                          avgt       3   4.010 ± 0.488   ms/op
ClientPb.listUser                         avgt       3   4.676 ± 0.290   ms/op
ClientPb.createUser                     sample  234993   4.084 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.499           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.602           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.398           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.869           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  246000   3.902 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.350           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.320           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.207           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  235423   4.076 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.669           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.825           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.598           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.965           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768           ms/op
ClientPb.listUser                       sample  201861   4.754 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.070           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.612           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.195           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.064           ms/op
