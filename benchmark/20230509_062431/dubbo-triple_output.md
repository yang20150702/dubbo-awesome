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
# Warmup Iteration   1: 1.522 ops/ms
# Warmup Iteration   2: 4.146 ops/ms
# Warmup Iteration   3: 7.313 ops/ms
Iteration   1: 7.609 ops/ms
Iteration   2: 8.244 ops/ms
Iteration   3: 7.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.944 ±(99.9%) 5.817 ops/ms [Average]
  (min, avg, max) = (7.609, 7.944, 8.244), stdev = 0.319
  CI (99.9%): [2.127, 13.761] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.427 ops/ms
# Warmup Iteration   2: 7.028 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.578 ops/ms
Iteration   2: 8.431 ops/ms
Iteration   3: 8.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.512 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (8.431, 8.512, 8.578), stdev = 0.075
  CI (99.9%): [7.146, 9.879] (assumes normal distribution)


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
# Warmup Iteration   1: 2.251 ops/ms
# Warmup Iteration   2: 6.250 ops/ms
# Warmup Iteration   3: 7.533 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 8.458 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.266 ±(99.9%) 3.481 ops/ms [Average]
  (min, avg, max) = (8.076, 8.266, 8.458), stdev = 0.191
  CI (99.9%): [4.785, 11.747] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.136 ops/ms
# Warmup Iteration   2: 5.924 ops/ms
# Warmup Iteration   3: 6.855 ops/ms
Iteration   1: 6.949 ops/ms
Iteration   2: 6.828 ops/ms
Iteration   3: 7.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.969 ±(99.9%) 2.793 ops/ms [Average]
  (min, avg, max) = (6.828, 6.969, 7.132), stdev = 0.153
  CI (99.9%): [4.177, 9.762] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.170 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.006 ms/op
Iteration   1: 3.886 ±(99.9%) 0.005 ms/op
Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
Iteration   3: 3.906 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.895 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.886, 3.895, 3.906), stdev = 0.010
  CI (99.9%): [3.709, 4.081] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.170 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.012 ms/op
Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
Iteration   3: 3.699 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.766 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (3.699, 3.766, 3.848), stdev = 0.076
  CI (99.9%): [2.379, 5.152] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.697 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.004 ms/op
Iteration   1: 3.998 ±(99.9%) 0.005 ms/op
Iteration   2: 3.944 ±(99.9%) 0.008 ms/op
Iteration   3: 3.963 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.968 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.944, 3.968, 3.998), stdev = 0.027
  CI (99.9%): [3.468, 4.468] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.696 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.855 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.704 ±(99.9%) 0.011 ms/op
Iteration   1: 4.455 ±(99.9%) 0.014 ms/op
Iteration   2: 4.535 ±(99.9%) 0.013 ms/op
Iteration   3: 4.493 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.494 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (4.455, 4.494, 4.535), stdev = 0.040
  CI (99.9%): [3.767, 5.221] (assumes normal distribution)


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
# Warmup Iteration   1: 12.600 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 5.064 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.017 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  14.593 ms/op
                 createUser·p0.9999: 24.833 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.561 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 3.968 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  27.259 ms/op
                 createUser·p0.9999: 30.472 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244211
  mean =      3.930 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 447 
    [ 2.500,  5.000) = 234346 
    [ 5.000,  7.500) = 7550 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.751 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     22.603 ms/op
     p(99.9900) =     29.010 ms/op
     p(99.9990) =     31.532 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 11.474 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
Iteration   1: 3.736 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  23.643 ms/op
                 existUser·p0.9999: 27.999 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.976 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.804 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 31.398 ms/op
                 existUser·p1.00:   32.178 ms/op

Iteration   3: 3.895 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.599 ms/op
                 existUser·p0.999:  26.903 ms/op
                 existUser·p0.9999: 30.532 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251570
  mean =      3.811 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 543 
    [ 2.500,  5.000) = 239680 
    [ 5.000,  7.500) = 10018 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     23.509 ms/op
     p(99.9900) =     30.147 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 12.784 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.014 ms/op
Iteration   1: 3.966 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.013 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   8.266 ms/op
                 getUser·p0.999:  23.572 ms/op
                 getUser·p0.9999: 28.574 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   2: 3.882 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 26.822 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   3: 3.935 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  25.876 ms/op
                 getUser·p0.9999: 34.053 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244331
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 107 
    [ 2.500,  5.000) = 232848 
    [ 5.000,  7.500) = 8750 
    [ 7.500, 10.000) = 2041 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.624 ms/op
     p(99.9000) =     23.473 ms/op
     p(99.9900) =     31.902 ms/op
     p(99.9990) =     34.414 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 12.853 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.516 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.644 ±(99.9%) 0.016 ms/op
Iteration   1: 4.818 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  24.543 ms/op
                 listUser·p0.9999: 26.914 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 4.603 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  17.318 ms/op
                 listUser·p0.9999: 22.030 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.628 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.006 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204927
  mean =      4.681 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 171008 
    [ 5.000,  7.500) = 28924 
    [ 7.500, 10.000) = 4008 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     18.877 ms/op
     p(99.9900) =     26.133 ms/op
     p(99.9990) =     27.622 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.944 ± 5.817  ops/ms
ClientPb.existUser                       thrpt       3   8.512 ± 1.366  ops/ms
ClientPb.getUser                         thrpt       3   8.266 ± 3.481  ops/ms
ClientPb.listUser                        thrpt       3   6.969 ± 2.793  ops/ms
ClientPb.createUser                       avgt       3   3.895 ± 0.186   ms/op
ClientPb.existUser                        avgt       3   3.766 ± 1.386   ms/op
ClientPb.getUser                          avgt       3   3.968 ± 0.500   ms/op
ClientPb.listUser                         avgt       3   4.494 ± 0.727   ms/op
ClientPb.createUser                     sample  244211   3.930 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.751           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.841           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.603           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.010           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  251570   3.811 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.583           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.509           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  244331   3.927 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.624           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.473           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.902           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  204927   4.681 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.554           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.133           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
