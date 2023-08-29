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
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 3.378 ops/ms
# Warmup Iteration   3: 6.749 ops/ms
Iteration   1: 7.446 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.876 ±(99.9%) 6.854 ops/ms [Average]
  (min, avg, max) = (7.446, 7.876, 8.142), stdev = 0.376
  CI (99.9%): [1.022, 14.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.145 ops/ms
# Warmup Iteration   2: 6.608 ops/ms
# Warmup Iteration   3: 8.384 ops/ms
Iteration   1: 7.966 ops/ms
Iteration   2: 8.152 ops/ms
Iteration   3: 8.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.282 ±(99.9%) 7.265 ops/ms [Average]
  (min, avg, max) = (7.966, 8.282, 8.730), stdev = 0.398
  CI (99.9%): [1.017, 15.548] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 6.727 ops/ms
# Warmup Iteration   3: 7.901 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 7.648 ops/ms
Iteration   3: 7.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.802 ±(99.9%) 3.213 ops/ms [Average]
  (min, avg, max) = (7.648, 7.802, 7.994), stdev = 0.176
  CI (99.9%): [4.589, 11.015] (assumes normal distribution)


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
# Warmup Iteration   1: 2.139 ops/ms
# Warmup Iteration   2: 5.919 ops/ms
# Warmup Iteration   3: 6.711 ops/ms
Iteration   1: 6.679 ops/ms
Iteration   2: 6.941 ops/ms
Iteration   3: 7.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.926 ±(99.9%) 4.387 ops/ms [Average]
  (min, avg, max) = (6.679, 6.926, 7.159), stdev = 0.240
  CI (99.9%): [2.539, 11.313] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.006 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.163 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.003 ms/op
Iteration   1: 4.092 ±(99.9%) 0.005 ms/op
Iteration   2: 3.945 ±(99.9%) 0.012 ms/op
Iteration   3: 3.950 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.996 ±(99.9%) 1.527 ms/op [Average]
  (min, avg, max) = (3.945, 3.996, 4.092), stdev = 0.084
  CI (99.9%): [2.468, 5.523] (assumes normal distribution)


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
# Warmup Iteration   1: 12.941 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.007 ms/op
Iteration   1: 3.775 ±(99.9%) 0.003 ms/op
Iteration   2: 3.715 ±(99.9%) 0.005 ms/op
Iteration   3: 3.732 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.741 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (3.715, 3.741, 3.775), stdev = 0.031
  CI (99.9%): [3.183, 4.299] (assumes normal distribution)


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
# Warmup Iteration   1: 14.389 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.007 ms/op
Iteration   1: 4.227 ±(99.9%) 0.005 ms/op
Iteration   2: 4.139 ±(99.9%) 0.009 ms/op
Iteration   3: 4.049 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.138 ±(99.9%) 1.624 ms/op [Average]
  (min, avg, max) = (4.049, 4.138, 4.227), stdev = 0.089
  CI (99.9%): [2.515, 5.762] (assumes normal distribution)


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
# Warmup Iteration   1: 14.744 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.006 ms/op
Iteration   1: 4.827 ±(99.9%) 0.007 ms/op
Iteration   2: 4.552 ±(99.9%) 0.012 ms/op
Iteration   3: 4.625 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.668 ±(99.9%) 2.596 ms/op [Average]
  (min, avg, max) = (4.552, 4.668, 4.827), stdev = 0.142
  CI (99.9%): [2.072, 7.265] (assumes normal distribution)


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
# Warmup Iteration   1: 13.285 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.282 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.020 ms/op
Iteration   1: 4.201 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  22.126 ms/op
                 createUser·p0.9999: 28.239 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 4.158 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.312 ms/op
                 createUser·p0.99:   7.382 ms/op
                 createUser·p0.999:  25.173 ms/op
                 createUser·p0.9999: 34.689 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   3: 4.050 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.897 ms/op
                 createUser·p0.999:  13.747 ms/op
                 createUser·p0.9999: 36.176 ms/op
                 createUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231950
  mean =      4.136 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 480 
    [ 2.500,  5.000) = 211878 
    [ 5.000,  7.500) = 16442 
    [ 7.500, 10.000) = 1968 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 57 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     36.593 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 11.639 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.012 ms/op
Iteration   1: 3.816 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.806 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  12.560 ms/op
                 existUser·p0.9999: 25.345 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 3.817 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.976 ms/op
                 existUser·p0.999:  13.415 ms/op
                 existUser·p0.9999: 26.882 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.769 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  26.460 ms/op
                 existUser·p0.9999: 29.657 ms/op
                 existUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252421
  mean =      3.801 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 636 
    [ 2.500,  5.000) = 240748 
    [ 5.000,  7.500) = 8396 
    [ 7.500, 10.000) = 1617 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     15.354 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     30.649 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 12.794 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.807 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.013 ms/op
Iteration   1: 4.176 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   9.617 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 22.219 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 4.315 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 4.329 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.091 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   10.322 ms/op
                 getUser·p0.999:  17.154 ms/op
                 getUser·p0.9999: 26.912 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 224571
  mean =      4.272 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 205 
    [ 2.500,  5.000) = 196553 
    [ 5.000,  7.500) = 21337 
    [ 7.500, 10.000) = 4614 
    [10.000, 12.500) = 1243 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     25.946 ms/op
     p(99.9990) =     27.615 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 16.002 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 5.892 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.754 ±(99.9%) 0.016 ms/op
Iteration   1: 4.854 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   9.757 ms/op
                 listUser·p0.999:  22.970 ms/op
                 listUser·p0.9999: 26.536 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.843 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   10.248 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 26.994 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   3: 4.849 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.996 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  17.206 ms/op
                 listUser·p0.9999: 19.982 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197924
  mean =      4.849 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 152549 
    [ 5.000,  7.500) = 37388 
    [ 7.500, 10.000) = 5850 
    [10.000, 12.500) = 1402 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     19.535 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.724 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.876 ± 6.854  ops/ms
ClientPb.existUser                       thrpt       3   8.282 ± 7.265  ops/ms
ClientPb.getUser                         thrpt       3   7.802 ± 3.213  ops/ms
ClientPb.listUser                        thrpt       3   6.926 ± 4.387  ops/ms
ClientPb.createUser                       avgt       3   3.996 ± 1.527   ms/op
ClientPb.existUser                        avgt       3   3.741 ± 0.558   ms/op
ClientPb.getUser                          avgt       3   4.138 ± 1.624   ms/op
ClientPb.listUser                         avgt       3   4.668 ± 2.596   ms/op
ClientPb.createUser                     sample  231950   4.136 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.548           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.151           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.855           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.865           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  252421   3.801 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.529           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.354           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.770           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.359           ms/op
ClientPb.getUser                        sample  224571   4.272 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.637           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.552           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.946           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  197924   4.849 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.207           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
